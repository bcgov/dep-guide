---
title: Internationalization and Language Switching
date: 2026-07-10 10:00:00 +0700
categories: [pages/features, engagement, features, language]
tags: [language switching, language, engagement]
---

Contents:

- [Switching Languages](#switching-languages)
  - [Switching Languages on the Public Page](#switching-languages-on-the-public-page)
  - [Switching Languages from the Authoring Pages](#switching-languages-from-the-authoring-pages)
- [Configuring an Engagement's Language](#configuring-an-engagements-language)
- [Managing Languages Globally (Admin only)](#managing-languages-globally-admin-only)

## Switching Languages

Switching languages looks a bit different between pages, but the functionality is the same.

### Switching Languages on the Public Page

On the public page, the language switcher button is located in the top right corner of the page, just under the navigation bar. It is represented by a globe icon, and contains the name of the currently selected language.

[!The language switcher button on the public page](/assets/UserGuideImages/Images/language-switching/public-switcher-location.png){: .light .shadow .rounded-10}

Note that you may not see the language switcher button if the engagement is only available in one language. In that case, the engagement will be displayed in that language by default.

[!An engagement with no language switcher button, because it is only available in one language](/assets/UserGuideImages/Images/language-switching/public-switcher-missing.png){: .light .shadow .rounded-10}

When you click on the language switcher button, a dropdown menu will appear with a list of available languages for that engagement. The currently selected language will be highlighted in the list.

[!The language switcher dropdown menu on the public page](/assets/UserGuideImages/Images/language-switching/public-switcher-dropdown.png){: .light .shadow .rounded-10}

Click on a language in the list to switch to that language. The page will load the translated content for that language.

[!The example engagement page with its language set to French](/assets/UserGuideImages/Images/language-switching/public-switcher-example-french.png){: .light .shadow .rounded-10}

> **Note:** We may not yet have translations available for all UI elements in all languages. In this case, the untranslated elements will be displayed in English.

### Switching Languages from the Authoring pages

When authoring an engagement, you can choose which language you are editing. From the main Authoring overview tab, you can select the language you want to edit from the language dropdown menu in the top right corner of the tab. The currently selected language will be displayed in the dropdown menu, accompanied by a globe icon.

[!The language switcher dropdown menu on the Authoring overview tab](/assets/UserGuideImages/Images/language-switching/authoring-switcher-location-authoring-tab.png){: .light .shadow .rounded-10}

Clicking on the language dropdown menu will display a list of available languages for that engagement. The currently selected language will be highlighted in the list.

[!The language switcher dropdown menu on the Authoring overview tab](/assets/UserGuideImages/Images/language-switching/authoring-switcher-dropdown-authoring-tab.png){: .light .shadow .rounded-10}

Note that you will not see the any changes in the Authoring overview tab. The title of the engagement will display in English, regardless of the selected language.

[!The Authoring overview tab with the language set to French, showing the unchanged English title of the engagement](/assets/UserGuideImages/Images/language-switching/authoring-switcher-example-french-authoring-tab.png){: .light .shadow .rounded-10}

However, when you navigate to a specific authoring section, such as the "Hero Banner" section, you will see the content for that section in the selected language, available for editing. The blue status bar at the bottom of the screen shows that the current language selected for authoring is French.

[!The Hero Banner section of the Authoring tab with the language set to French, showing the translated content for that section](/assets/UserGuideImages/Images/language-switching/authoring-switcher-example-french-authoring-page.png){: .light .shadow .rounded-10}

Similar to before, the dropdown menu in the status bar allows you to switch between available languages for that engagement. The currently selected language will be highlighted in the list.

[!The language switcher dropdown menu in the status bar of the Authoring tab](/assets/UserGuideImages/Images/language-switching/authoring-switcher-dropdown-authoring-page.png){: .light .shadow .rounded-10}

If only English is available for the engagement, the language switcher dropdown menu will be grayed out and unclickable, and the status bar will display "English" as the current language.

[!The language switcher dropdown menu in the status bar of the Authoring tab, grayed out because only English is available](/assets/UserGuideImages/Images/language-switching/authoring-switcher-disabled-authoring-page.png){: .light .shadow .rounded-10}

## Configuring an Engagement's Language

When creating a new engagement, you can select the languages that will be available for use (authoring + viewing) elsewhere in the engagement. English is available by default and cannot be removed. If you wish to configure additional languages for the engagement, select the "multi-language" option in configuration step 4 ("Will your engagement be offered in multiple languages?").

If you are editing an existing engagement, you can configure the available languages by navigating to the "Configuration" tab of the engagement, then hit the "Edit Configuration" button at the bottom. If it is not already, switch the language setting from English Only to Multi-Language. Then, proceed as you would when creating a new engagement.

[!The language configuration options when creating a new engagement](/assets/UserGuideImages/Images/language-switching/configure-languages-new-engagement.png){: .light .shadow .rounded-10}

Then, select a language you wish to add from the list of available languages. Then, press "Add Language" to add the language to the engagement. You can repeat this process to add multiple languages.

[!The language configuration options when creating a new engagement with the dropdown expanded, showing the list of available languages](/assets/UserGuideImages/Images/language-switching/configure-languages-language-dropdown.png){: .light .shadow .rounded-10}

[!The language configuration options when creating a new engagement with French selected to be added to the engagement. The "Add Language" button is highlighted to indicate that it can be clicked to add the language](/assets/UserGuideImages/Images/language-switching/configure-languages-add-french.png){: .light .shadow .rounded-10}

Once a language has been added to the engagement, it will appear in the list of selected languages. You can remove a language (except English) from the engagement by clicking the "x" button next to the language in the list. Don't forget to save your changes with the button at the bottom of the form.

[!The language configuration options when creating a new engagement with French added to the engagement. The "x" button next to French is highlighted to indicate that it can be clicked to remove the language](/assets/UserGuideImages/Images/language-switching/configure-languages-french-added.png){: .light .shadow .rounded-10}

## Managing Languages Globally (Admin only)

To change the available languages that can be selected for engagements in your tenant, navigate to the "Languages" tab on the left side of most pages. This tab is only available to users with the "Admin" role. From this page, you can add or remove languages that will be available for selection when creating or editing engagements.

[!The Languages tab in the Admin section, showing the list of available languages](/assets/UserGuideImages/Images/language-switching/admin-languages-tab.png){: .light .shadow .rounded-10}

Select a language from the dropdown menu to add it to the list of available languages. To remove a language, click the "x" button next to the language in the list. Changes on this page are saved automatically.

If we are missing a language that you expect to see, please contact your account manager to request that it be added.
