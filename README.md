- [Workflow 1: How to Add Styled Images to Your Post](#image-flow)
- [Workflow 2: How to Use Data-Driven Content in Your Posts](#data-flow)
- [Appendix: Cleaning Up Post Assets with find_widows](#appendix)
{: .workflow-menu}

This guide walks through **two typical post workflows**READMORE:

1. **Images + Stylesheets** – fetching images into a per‑post directory, and creating a page‑scoped stylesheet.
2. **Post Data** – generating a sample data file with a rake task, and ERB code that injects the YAML data as markdown text.

Each workflow illustrates how Roji adopts per-post asset directories to keep content structured, self-contained, and easy to manage.

**Step 0:** At the moment we need the micro-optparse gem installed, globally.
Check for its presence with `gem list micro-optparse`. Install the gem via
`gem install micro-optparse`, it's quite tiny.

# How to Add Styled Images to Your Post
{: #image-flow}
