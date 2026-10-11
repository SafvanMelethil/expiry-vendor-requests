# Expiry Vendor Requests

Web app to build expiry vendor return requests from the SAP stock sheet.

1. Upload the stock Excel (Material, Material Description, Plant, Storage Location, Batch, Unrestriced Quantity, Expiration Date, Supplier, Vendor Name, Cost Price).
2. Click **Create vendor request**, search any field, pick a material, enter qty and batch.
3. First material locks the supplier. Short batches show recommended batches/locations.
4. **Export Excel** gives two sheets: *Vendor Request* and *Batch Change*.

Everything runs in the browser. The uploaded stock file is never sent to any server; it stays on the user's own computer.
