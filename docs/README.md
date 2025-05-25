# **Fortune Cookies Store Theme**

A storefront built with **VTEX IO Store Framework** focused on a playful _“Fortune-cookie”_ experience.  
Within this store you can find:

* Responsive **3-card CTA** leading to a fortune-cookie landing.
* Seasonal **hero slider** (controlled in CMS).
* A dedicated landing for the fortune cookie component.

---

## Preview

<div align="center">
  <img width="330" src="https://github.com/user-attachments/assets/fa0eb23a-04be-4e00-b844-690774eb0bf2" />
  <img width="330" src="https://github.com/user-attachments/assets/88c53cc2-7133-46f0-b782-847dab122ba2" />
  <img width="330" alt="image" src="https://github.com/user-attachments/assets/48c37850-ea74-4f3b-a75a-73a4cfe161d5" />
</div>

## 

<img width="1505" alt="image" src="https://github.com/user-attachments/assets/65d69ed7-f7e5-44d3-b6df-6f47a488a9cd" />

---

## Getting started

### 1. Basic setup

Follow the official [VTEX IO basic setup](https://developers.vtex.com/docs/guides/vtex-io-documentation-1-basicsetup).  
You should end with Toolbelt installed and a dev workspace ready.

### 2. Clone the repository

[Clone this](https://github.com/mosqueradvd/valtech-fortune-cookies-store-theme.git) repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal.

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "valtech",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

## Dependencies

All store components that you see on this document are open source too. Production ready, you can found those apps in this GitHub organization.

Store framework is the baseline to create any store using _VTEX IO Web Framework_.
- [Store](https://github.com/vtex-apps/store/blob/master/README.md)

### Store component dependencies
- [Header](https://github.com/vtex-apps/store-header/blob/master/docs/README.md)
- [Footer](https://github.com/vtex-apps/store-footer/blob/master/docs/README.md)
- [Slider Layout](https://github.com/vtex-apps/slider-layout/blob/master/docs/README.md)
- [Shelf](https://github.com/vtex-apps/shelf/blob/master/docs/README.md)
- [Telemarketing](https://github.com/vtex-apps/telemarketing/blob/master/docs/README.md)
- [Menu](https://github.com/vtex-apps/menu/blob/master/docs/README.md)
- [Login](https://github.com/vtex-apps/login/blob/master/docs/README.md)
- [Minicart](https://github.com/vtex-apps/minicart/blob/master/docs/README.md)
- [Category Menu](https://github.com/vtex-apps/category-menu/blob/master/docs/README.md)
- [Product Summary](https://github.com/vtex-apps/product-summary/blob/master/docs/README.md)
- [Breadcrumb](https://github.com/vtex-apps/breadcrumb/blob/master/docs/README.md)
- [Search Result](https://github.com/vtex-apps/search-result/blob/master/docs/README.md)
- [Product Details](https://github.com/vtex-apps/product-details/blob/master/docs/README.md)
- [Store Components](https://github.com/vtex-apps/store-components/blob/master/docs/README.md)
- [Order Placed](https://github.com/vtex-apps/order-placed/blob/master/docs/README.md)

### Custom component dependencies
[Fortune Cookies Component](https://github.com/mosqueradvd/valtech-fortune-cookies-store-app)

```json
"valtech.fortune-cookies": "0.x"
```

### Peer store component dependencies

None.
