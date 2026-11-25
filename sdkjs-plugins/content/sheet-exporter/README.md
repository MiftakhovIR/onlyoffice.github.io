# Sheet Exporter

Export worksheets from a local XLSX to XLSX or ZIP. Supports basic formatting, merges, row/column sizes and filters. Does not modify the source workbook. Formula preservation is experimental; advanced workbook features are not supported.

Automatic editor download is disabled by default. Only an administrator who has verified download authorization for all affected sessions should enable it in policy.js. The automatic mode requires same-origin download URLs. Installation from the marketplace has not been tested on a live Document Server.

The official ONLYOFFICE plugin SDK is loaded from https://onlyoffice.github.io/sdkjs-plugins/v1/plugins.js; workbook processing does not send data to an external service.
