# HELM Longevity — mobile preview

Static HTML preview for testing the mobile interface. This demo stores entered data only in the current browser with localStorage. It has no employee accounts, server database, or HELM AI connection. Do not enter real employee health data.

The welcome/login screen is a visual preview. **“ทดลองเข้าสู่ Home” does not authenticate anyone.** The company sign-in button is disabled until an approved SSO connection is implemented. To revisit the welcome screen, choose **ฉัน → ออกจากพรีวิว**, or open the preview URL with `?login=1`.

The intranet application and server remain separate from this preview.

The preview is packaged as one self-contained `index.html`, including its display font, logo, and mascot images.
