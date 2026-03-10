## Ratebooks
The main prupose of most of these tabs is to adjust prices (base or factor) given different trip parameters.  
For example: two tabs might both have price adjustments. One tab might tie the price adjustments to Zones and Car class,
while the other tab might tie the price adjustments to Areas Time Slice.

> [!note]
> Other than the (Tab 1), you can double-click a row to modify the data behind it or its parameters.

### List Groups Setup (Tab 2)
- This tab shows **List Price Groups** (or List Groups), which are units that combine:
  - Ratebook
  - PU and DO location type (AP, MN, OT...)
  - and Car class

### Pricing Setup (Tab 1)
- This tab shows the price of trips given PU and DO zones.
- All further adjustments (other tabs) are based on this initial value.
- Interact with the left section to change the Area.
- Interact witht the dropdown on the top-right to change the **List Price Groups**.

> [!caution]
> Do not undo the contents of this table by pressing [Esc], use the dedicated button "red x".  
> Otherwise, the tabs will stay dissabled.

### Base Price Setup (Tab 3)
- This tab shows price adjustments (base amounts and multiplcation factors).
- The price adjustments are tied to PU-DO **area**, Car class, and **List Price Group**.

### By The Hour Setup (Tab 4)
- This tab shows hourly rates and other parameters related to hourly rates.

### List Price Adjustments (Tab 5)
- This tab shows price adjustments (base amounts).
- The price adjustments are tied to PU **zone**, DO **zone**, and **List Price Group**

### Airport Adjustments (Tab 6)
- This tab shows price adjustments (base amounts)
- The price adjustments are tied to Airport Code, PU type (IN, OUT), and Car class.
- Top table has adjustments based on PU type (IN, OUT). Bottom table on Time Slice.

### Base Price Formula Setup (Tab 7)
- This tab shows price adjustments (base amounts and multiplcation factors).
- The price adjustments are tied to PU **zone**, DO **zone**, Car class.

### Time Slice Setup (Tab 8)
- This tab defines time slices
- The table's dates define when the time slice first comes into effect and when it should end.
- Double-clicking a time slice allows you to edit the actual time window within the day that the time slice is in effect.
