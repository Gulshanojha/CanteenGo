I built the app as one working page, and it’s published as an artifact
Menu: 16 items in 4 categories, 4 of them sold out. Search, category and veg/non-veg filters all work together. 
Sold-out items have a disabled button. There is an empty state for no search results.
Cart and checkout: You can add, remove and change quantity, and totals update instantly. 
The cart is saved in localStorage. The form validates name, roll number, pickup slot and payment method, with 
inline error messages and focus moving to the first error. Choosing Card fails once so you can see the “payment failed” state, 
and the retry succeeds.
Tracking: The order number and status steps (Placed → Preparing → Ready → Picked up) advance every 8 seconds. 
The order survives a refresh.
Accessibility and layout: It uses real buttons, labels and a fieldset, and keyboard focus is visible.
Every emoji illustration has alt text. The colour pairs were chosen for AA contrast, but I haven’t measured them. 
The layout is responsive, and a dark mode toggle is included.
Bonus: Dark mode and reduced-motion support are in. The staff view and the usability test are not.
