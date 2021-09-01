# Keeping internal documentation up to date
Enterprises often keep internal documentation about processes, tools, work procedures, architectures. The documentation is kept in systems like Atlassian Confluence, GitLab, GitHub, Wiki. These systems make it easy to create content and share it. The problem is that content is not kept up to date, not spell checked, not structured. It is like a library that is growing every day but there is no librarian. This is an industry problem - investigating and implementing a solution to this could be a game changer.

The idea of this thesis is to investigate:
- Investigate how to implement a tool to keep content up to date
- Focus on Confluence and GitLab to start with
- Implement a tool that will parse all pages on a Confluence site and all Markdown pages throughout all project in a GitLab instance
- Let the tool spell check the content and do grammar review to give it a language rating
- Give the tool permissions to update content through Merge Requrests in GitLab
- Add metadata on each page with info about author, last edited, last reviewed
- Update through email or Slack when a page is missing metadata
- Update author via email/slack if a page hasn't been updated in X months
- Add a review process possibly with modifications to the process based on tags
- Have some kind of tagging system to classify information, examples:
  - Personal (no review)
  - Enforced Process (requires ackknowledge that X has read)
  - Process 
  - Document
