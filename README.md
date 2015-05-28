# DownloadExcel
A jquery plugin for download html table into excel .xls format

$('table').downloadExcel() creates xls file with the content of your table and force downloads.

You can fire it up on click event.

$('#downloadBtn').click(function(){ $('table').downloadExcel( 'your-file-name' ) })
