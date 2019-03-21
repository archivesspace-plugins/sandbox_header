# sandbox_header

A sticky alert header for sandbox.archivesspace.org.

## To install:

1. Stop the application
2. Clone the plugin into the `archivesspace/plugins` directory
3. Add `sandbox_header` to `config.rb`, ensuring to uncomment/remove the # from the front of the relevant AppConfig line.  For example:
`AppConfig[:plugins] = ['local', 'sandbox_header']`
4. Restart the application
