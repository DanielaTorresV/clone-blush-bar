# Blush-Bar Store

This store is a makeup and beauty store based on a minimum boilerplate theme of VTEX

HEADER MOBILE

![image](https://user-images.githubusercontent.com/101153916/195952948-250c84c5-a068-48ae-b30f-aef838842f63.png)

HEADER DESKTOP

![image](https://user-images.githubusercontent.com/101153916/195952854-5a505086-1e43-418b-b6da-258807edcc13.png)

FOOTER MOBILE

![image](https://user-images.githubusercontent.com/101153916/195953013-649a5a4e-16ae-4674-907c-479c9c95ee75.png)

FOOTER DESKTOP

![image](https://user-images.githubusercontent.com/101153916/195952889-119104a2-0aad-4944-be5d-d435e3f01680.png)

HOME PHONE
HOME TABLET
HOME DESKTOP

## Configuration

### Step 1 - Basic setup

If you need to intall VTEX in your terminal you follow the next steps.

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps.

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

You can do a store from the beginning [Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to
your local files to be able to effectively start working on it. Or clone this repository to work in a beauty store.

Then, access the repository's directory using your terminal.

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file.

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to
name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme"
}
```

### Step 4 - Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run `vtex list` and check whether those apps are already installed.

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 - Uninstalling any existing theme

By running `vtex list`, you can verify if any theme is installed.

It is common to already have a `vtex.store-theme` installed when you start the store's front development process.

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command.

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser
window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

## Dependencies

1. Store minumun boilerplate theme
2. Store GraphQl

## Peer Dependencies

1.  "vtex.wish-list": "1.x"
2.  "vtex.reviews-and-ratings": "3.x"
3.  "vtex.questions-and-answers": "0.x"

## Store Component Apps

1. "vtex.store": "2.x"
2. "vtex.store-header": "2.x"
3. "vtex.product-summary": "2.x"
4. "vtex.store-footer": "2.x"
5. "vtex.store-components": "3.x"
6. "vtex.styleguide": "9.x"
7. "vtex.slider": "0.x"
8. "vtex.shelf": "1.x"
9. "vtex.menu": "2.x"
10. "vtex.minicart": "2.x"
11. "vtex.product-details": "1.x"
12. "vtex.search-result": "3.x"
13. "vtex.login": "2.x"
14. "vtex.my-account": "1.x"
15. "vtex.flex-layout": "0.x"
16. "vtex.rich-text": "0.x"
17. "vtex.store-drawer": "0.x"
18. "vtex.locale-switcher": "0.x"
19. "vtex.product-quantity": "1.x"
20. "vtex.product-identifier": "0.x"
21. "vtex.product-specification-badges": "0.x"
22. "vtex.product-review-interfaces": "1.x"
23. "vtex.order-placed": "2.x"
24. "vtex.tab-layout": "0.x"
25. "vtex.responsive-layout": "0.x"
26. "vtex.slider-layout": "0.x"
27. "vtex.iframe": "0.x"
28. "vtex.breadcrumb": "1.x"
29. "vtex.sticky-layout": "0.x"
30. "vtex.add-to-cart-button": "0.x"
31. "vtex.store-link": "0.x"
32. "vtex.search": "2.x"
33. "vtex.store-icons": "0.x"
34. "vtex.store-newsletter": "1.x"
35. "vtex.checkout-summary": "0.x"
36. "vtex.product-list": "0.x"
37. "vtex.product-price": "1.x"
38. "vtex.modal-layout": "0.x"

## Custom Apps

1. "itgloberspartnercl.whatsapp-button": "0.x"
2. "itgloberspartnercl.bullets-diagramation": "0.x"
3. "itgloberspartnercl.add-to-cart-info": "0.x"
4. "itgloberspartnercl.custom-department-search": "0.x"
5. "itgloberspartnercl.pdf-reader": "0.x"
6. "itgloberspartnercl.quick-order": "0.x"
7. "itgloberspartnercl.special-diagramation": "0.x"

## Contributors

1. Daniela María Torres Vélez
