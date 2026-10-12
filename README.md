# Splunk Lead Upload Converter — Beta

Browser-only converter for one selected attendee worksheet into a reviewable Marketo Non-Partner CSV.

## Privacy

The workbook is parsed in your browser and is not uploaded to this site or saved by a backend. The page loads SheetJS from jsDelivr to read Excel files; workbook rows are not sent to that library host.

## Beta limitations

- One selected worksheet at a time.
- Non-Partner attendee lists only.
- Uses the schema snapshot observed 2026-10-01; verify against the latest SharePoint template before operational use.
- Does not connect to Salesforce to verify campaign status, hierarchy, type, or picklists.
- Review every output row and campaign detail before sending to Workfront.
- No submission to Workfront, Marketo, Salesforce, or Openprise.

The site is public to anyone with its URL. Use only data approved for this beta environment.
