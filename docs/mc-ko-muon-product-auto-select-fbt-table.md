# MC doesn't want product to be auto-selected in FBT table

**Category:** Customization request

---

## Issue

MC doesn't want products to be auto-selected in the FBT (Frequently Bought Together) table.

![FBT table with auto-selected products](image.png)

---

## Root Cause



---

## Solution

CS can enable the **"Allow untick FBT"** option in `dev_zone`:

![Enable Allow untick FBT in dev_zone](image%201.png)

Once enabled, MC can manually toggle the auto-select behavior in FBT settings:

![FBT setting toggle](image%202.png)

After disabling the feature, offer items on the front store will be automatically unticked:

![Front store items unticked](image%203.png)
