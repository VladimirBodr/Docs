---
title: "Basic Development"
_old_id: "31"
_old_uri: "2.x/developing-in-modx/basic-development/"
---

This section is geared at familiarizing developers with basic MODX development principles, and using the structures in MODX to create dynamic, script-driven content.

1. [Snippets](/revolution/2.x/developing-in-modx/basic-development/snippets)
  1. [Templating Your Snippets](/revolution/2.x/developing-in-modx/basic-development/snippets/templating-your-snippets)
  2. [Adding CSS and JS to Your Pages Through Snippets](/revolution/2.x/developing-in-modx/basic-development/snippets/adding-css-and-js-to-your-pages-through-snippets)
  3. [How to Write a Good Snippet](/revolution/2.x/developing-in-modx/basic-development/snippets/how-to-write-a-good-snippet)
  4. [How to Write a Good Chunk](/revolution/2.x/developing-in-modx/basic-development/snippets/how-to-write-a-good-chunk)
2. [Plugins](/revolution/2.x/developing-in-modx/basic-development/plugins)
  1. [System Events](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events)
      1. [OnBeforeCacheUpdate](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforecacheupdate)
      2. [OnBeforeChunkFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforechunkformdelete)
      3. [OnBeforeChunkFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforechunkformsave)
      4. [OnBeforeDocFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforedocformdelete)
      5. [OnBeforeDocFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforedocformsave)
      6. [OnBeforeManagerLogout](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforemanagerlogout)
      7. [OnBeforeSaveWebPageCache](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforesavewebpagecache)
      8. [OnBeforeWebLogout](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeweblogout)
      9. [OnCacheUpdate](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncacheupdate)
      10. [OnChunkFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkformdelete)
      11. [OnChunkFormPrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkformprerender)
      12. [OnChunkFormRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkformrender)
      13. [OnChunkFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkformsave)
      14. [OnDocFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocformdelete)
      15. [OnDocFormPrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocformprerender)
      16. [OnDocFormRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocformrender)
      17. [OnDocFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocformsave)
      18. [OnDocPublished](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocpublished)
      19. [OnDocUnPublished](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ondocunpublished)
      20. [OnLoadWebPageCache](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onloadwebpagecache)
      21. [OnManagerLogin](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerlogin)
      22. [OnManagerLogout](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerlogout)
      23. [OnSiteRefresh](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onsiterefresh)
      24. [OnUserChangePassword](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserchangepassword)
      25. [OnWebLogin](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onweblogin)
      26. [OnWebLogout](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onweblogout)
      27. [OnWebPagePrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onwebpageprerender)
      28. [OnManagerPageBeforeRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerpagebeforerender)
      29. [OnTemplateVarBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ontemplatevarbeforesave)
      30. [OnTemplateVarSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ontemplatevarsave)
      31. [OnTemplateVarBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ontemplatevarbeforeremove)
      32. [OnTemplateVarRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/ontemplatevarremove)
      33. [OnBeforeEmptyTrash](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeemptytrash)
      34. [OnBeforeManagerLogin](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforemanagerlogin)
      35. [OnBeforeManagerPageInit](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforemanagerpageinit)
      36. [OnBeforePluginFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforepluginformdelete)
      37. [OnBeforePluginFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforepluginformsave)
      38. [OnBeforeSnipFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforesnipformdelete)
      39. [OnBeforeSnipFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforesnipformsave)
      40. [OnBeforeTempFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforetempformdelete)
      41. [OnBeforeTempFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforetempformsave)
      42. [OnBeforeTVFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforetvformdelete)
      43. [OnBeforeTVFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforetvformsave)
      44. [OnBeforeUserActivate](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeuseractivate)
      45. [OnBeforeUserFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeuserformdelete)
      46. [OnBeforeUserFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeuserformsave)
      47. [OnBeforeWebLogin](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onbeforeweblogin)
      48. [OnCategoryBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncategorybeforeremove)
      49. [OnCategoryBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncategorybeforesave)
      50. [OnCategoryRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncategoryremove)
      51. [OnCategorySave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncategorysave)
      52. [OnChunkBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkbeforeremove)
      53. [OnChunkBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkbeforesave)
      54. [OnChunkRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunkremove)
      55. [OnChunkSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onchunksave)
      56. [OnContextBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextbeforeremove)
      57. [OnContextBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextbeforesave)
      58. [OnContextFormPrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextformprerender)
      59. [OnContextFormRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextformrender)
      60. [OnContextRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextremove)
      61. [OnContextSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oncontextsave)
      62. [OnEmptyTrash](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onemptytrash)
      63. [OnFileManagerUpload](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onfilemanagerupload)
      64. [OnHandleRequest](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onhandlerequest)
      65. [OnInitCulture](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/oninitculture)
      66. [OnLoadWebDocument](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onloadwebdocument)
      67. [OnManagerAuthentication](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerauthentication)
      68. [OnManagerLoginFormPrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerloginformprerender)
      69. [OnManagerLoginFormRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerloginformrender)
      70. [OnManagerPageAfterRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerpageafterrender)
      71. [OnManagerPageInit](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onmanagerpageinit)
      72. [OnPageNotFound](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpagenotfound)
      73. [OnPageUnauthorized](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpageunauthorized)
      74. [OnParseDocument](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onparsedocument)
      75. [OnPluginBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginbeforeremove)
      76. [OnPluginBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginbeforesave)
      77. [OnPluginEventRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onplugineventremove)
      78. [OnPluginFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginformdelete)
      79. [OnPluginFormPrerender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginformprerender)
      80. [OnPluginFormRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginformrender)
      81. [OnPluginFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginformsave)
      82. [OnPluginRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginremove)
      83. [OnPluginSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpluginsave)
      84. [OnPropertySetBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpropertysetbeforeremove)
      85. [OnPropertySetBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpropertysetbeforesave)
      86. [OnPropertySetRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpropertysetremove)
      87. [OnPropertySetSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onpropertysetsave)
      88. [OnResourceGroupBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onresourcegroupbeforeremove)
      89. [OnResourceGroupBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onresourcegroupbeforesave)
      90. [OnResourceGroupRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onresourcegroupremove)
      91. [OnResourceGroupSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onresourcegroupsave)
      92. [OnRichTextBrowserInit](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onrichtextbrowserinit)
      93. [OnRichTextEditorInit](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onrichtexteditorinit)
      94. [OnRichTextEditorRegister](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onrichtexteditorregister)
      95. [OnSiteSettingsRender](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onsitesettingsrender)
      96. [OnUserActivate](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuseractivate)
      97. [OnUserBeforeRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserbeforeremove)
      98. [OnUserBeforeSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserbeforesave)
      99. [OnUserFormDelete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserformdelete)
      100. [OnUserFormSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserformsave)
      101. [OnUserNotFound](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onusernotfound)
      102. [OnUserRemove](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onuserremove)
      103. [OnUserSave](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onusersave)
      104. [OnWebAuthentication](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onwebauthentication)
      105. [OnWebPageComplete](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onwebpagecomplete)
      106. [OnWebPageInit](/revolution/2.x/developing-in-modx/basic-development/plugins/system-events/onwebpageinit)
3. [xPDO](/revolution/2.x/developing-in-modx/basic-development/xpdo)