
EE Concierge + Altium Library Install Instruction:

The following are the instructions for loading a library that was exported from EE Concierge into Altium.

The library will come as a zip file filled with all the necessary Altium data files required to load your EE Concierge parts into Altium. For every part there will be a pcb file, and a schematic file. There will also be an index file, a readme file, and finally the master library file itself. Do not try to open any of the individual part files, or the index file as they can't be loaded on their own.

Instead, to load a library you simply need to point Altium to this master library file named: 'EEConcierge.DbLib'. There are two ways to do this which we outline below. Whenever you need to load an updated version of your EE Concierge library the instructions are exactly the same. We've tagged the parts exports in such a way that Altium will overwrite and update any previously loaded parts as opposed to creating duplicates.

Method A:

1) Unzip the exported library
2) Double click on the file 'EEConcierge.DbLib'
3) Altium will open and load the library for you, you can now use your new components

Method B:

1) Unzip the exported library
2) Open Altium Designer
3) In the 'File' menu, click 'Open'
4) Browse to the unzipped library directory, select 'EEConcierge.DbLib' and click 'Open'


Altium will load the library, you can now use your new components
Part DF11CZ-16DS-2V(22) (component id 4e7735cfc6ffb966) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 404 Client Error: 404 for url: https://www.hirose.com/product/en/download_file/key_name/DF11CZ-16DS-2V%2822%29/category/Drawing%20(2D)/doc_file_id/39833/?file_category_id=6&item_id=05432069722&is_series=


Part SIP-007AFS001 (component id 4cf02d8db5d305c7) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 403 Client Error: Forbidden for url: http://media.digikey.com/pdf/Data%20Sheets/Samsung%20PDFs/Artik710_DS.pdf


Part CYBLE-012011-00 (component id 0bd5075065089218) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 301, in save_datasheet
    r = requests.get(url, headers=headers, timeout=15)
  File "/usr/lib/python2.7/dist-packages/requests/api.py", line 72, in get
    return request('get', url, params=params, **kwargs)
  File "/usr/lib/python2.7/dist-packages/requests/api.py", line 58, in request
    return session.request(method=method, url=url, **kwargs)
  File "/usr/lib/python2.7/dist-packages/requests/sessions.py", line 520, in request
    resp = self.send(prep, **send_kwargs)
  File "/usr/lib/python2.7/dist-packages/requests/sessions.py", line 630, in send
    r = adapter.send(request, **kwargs)
  File "/usr/lib/python2.7/dist-packages/requests/adapters.py", line 521, in send
    raise ReadTimeout(e, request=request)
ReadTimeout: HTTPConnectionPool(host='www.cypress.com', port=80): Read timed out. (read timeout=15)


Part CPC1927J (component id 0b343085ae731b77) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 404 Client Error: Not Found for url: https://www.ixysic.com:443/home/pdfs.nsf/www/CPC1927.pdf/$file/CPC1927.pdf


Part 10118194-0001LF (component id 38abf8eea34355f5) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 503 Server Error: Service Temporarily Unavailable for url: https://www.amphenol-icc.com


Part ERJ-3EKF22R0V (component id 37a867720ea5b767) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 404 Client Error: Not Found for url: https://industrial.panasonic.com/cdbs/www-data/pdf/RDA0000/AOA0000C283.pdf


Part L7805CDT-TR (component id bb154d111f923c04) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 404 Client Error: Not Found for url: https://www.tme.eu/Document/f6092a52464df9e2325fb217956cf4b6/L78xx.pdf


Part ADV7180BSTZ (component id be9261dbc82c7aa9) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 403 Client Error: Forbidden for url: http://media.digikey.com/pdf/Data%20Sheets/Analog%20Devices%20PDFs/ADV7180.pdf


Part GYPRO3300 (component id 19ca389d261746da) experienced an error during datasheet export:
Traceback (most recent call last):
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 407, in export_datasheet
    datasheets[datasheet_url] = self.save_datasheet(datasheet_url)
  File "/home/upverter/schematic-file-converter/upconvert/writer/altium/altium.py", line 302, in save_datasheet
    r.raise_for_status()
  File "/usr/lib/python2.7/dist-packages/requests/models.py", line 935, in raise_for_status
    raise HTTPError(http_error_msg, response=self)
HTTPError: 404 Client Error: Not Found for url: http://www.tronicsgroup.com/IMG/pdf/mcd002-b_datasheet_dsg3300_rev_1.2-2.pdf


