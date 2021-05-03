### Hi there 👋

- uses: lowlighter/metrics@latest
  with:
    # ... other options
    plugin_languages: yes
    plugin_languages_ignored: html, css                          # List of languages to ignore
    plugin_languages_skipped: my-test-repo                       # List of repositories to skip
    plugin_languages_colors: "0:orange, javascript:#ff0000, ..." # Make most used languages orange and JavaScript red
    plugin_languages_details: bytes-size, percentage             # Additionally display total bytes size and percentage
    plugin_languages_threshold: 2%                               # Hides all languages less than 2%
    plugin_languages_limit: 8                                    # Display up to 8 languages
