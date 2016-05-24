<?xml version="1.0" encoding="utf-8"?>
<resources>
    <attr format="reference" name="drawerArrowStyle"/>
    <attr format="dimension" name="height"/>
    <attr format="boolean" name="isLightTheme"/>
    <attr format="string" name="title"/>
    <bool name="abc_action_bar_embed_tabs">true</bool>
    <bool name="abc_action_bar_embed_tabs_pre_jb">false</bool>
    <bool name="abc_action_bar_expanded_action_views_exclusive">true</bool>
    <bool name="abc_allow_stacked_button_bar">true</bool>
    <bool name="abc_config_actionMenuItemAllCaps">true</bool>
    <bool name="abc_config_allowActionMenuItemTextWithIcon">false</bool>
    <bool name="abc_config_closeDialogWhenTouchOutside">true</bool>
    <bool name="abc_config_showMenuShortcutsWhenKeyboardPresent">false</bool>
    <color name="abc_input_method_navigation_guard">@android:color/black</color>
    <color name="abc_search_url_text_normal">#7fa87f</color>
    <color name="abc_search_url_text_pressed">@android:color/black</color>
    <color name="abc_search_url_text_selected">@android:color/black</color>
    <color name="accent_material_dark">@color/material_deep_teal_200</color>
    <color name="accent_material_light">@color/material_deep_teal_500</color>
    <color name="background_floating_material_dark">@color/material_grey_800</color>
    <color name="background_floating_material_light">@android:color/white</color>
    <color name="background_material_dark">@color/material_grey_850</color>
    <color name="background_material_light">@color/material_grey_50</color>
    <color name="bright_foreground_disabled_material_dark">#80ffffff</color>
    <color name="bright_foreground_disabled_material_light">#80000000</color>
    <color name="bright_foreground_inverse_material_dark">@color/bright_foreground_material_light</color>
    <color name="bright_foreground_inverse_material_light">@color/bright_foreground_material_dark</color>
    <color name="bright_foreground_material_dark">@android:color/white</color>
    <color name="bright_foreground_material_light">@android:color/black</color>
    <color name="button_material_dark">#ff5a595b</color>
    <color name="button_material_light">#ffd6d7d7</color>
    <color name="dim_foreground_disabled_material_dark">#80bebebe</color>
    <color name="dim_foreground_disabled_material_light">#80323232</color>
    <color name="dim_foreground_material_dark">#ffbebebe</color>
    <color name="dim_foreground_material_light">#ff323232</color>
    <color name="foreground_material_dark">@android:color/white</color>
    <color name="foreground_material_light">@android:color/black</color>
    <color name="highlighted_text_material_dark">#6680cbc4</color>
    <color name="highlighted_text_material_light">#66009688</color>
    <color name="hint_foreground_material_dark">@color/bright_foreground_disabled_material_dark</color>
    <color name="hint_foreground_material_light">@color/bright_foreground_disabled_material_light</color>
    <color name="material_blue_grey_800">#ff37474f</color>
    <color name="material_blue_grey_900">#ff263238</color>
    <color name="material_blue_grey_950">#ff21272b</color>
    <color name="material_deep_teal_200">#ff80cbc4</color>
    <color name="material_deep_teal_500">#ff009688</color>
    <color name="material_grey_100">#fff5f5f5</color>
    <color name="material_grey_300">#ffe0e0e0</color>
    <color name="material_grey_50">#fffafafa</color>
    <color name="material_grey_600">#ff757575</color>
    <color name="material_grey_800">#ff424242</color>
    <color name="material_grey_850">#ff303030</color>
    <color name="material_grey_900">#ff212121</color>
    <color name="primary_dark_material_dark">@android:color/black</color>
    <color name="primary_dark_material_light">@color/material_grey_600</color>
    <color name="primary_material_dark">@color/material_grey_900</color>
    <color name="primary_material_light">@color/material_grey_100</color>
    <color name="primary_text_default_material_dark">#ffffffff</color>
    <color name="primary_text_default_material_light">#de000000</color>
    <color name="primary_text_disabled_material_dark">#4Dffffff</color>
    <color name="primary_text_disabled_material_light">#39000000</color>
    <color name="ripple_material_dark">#33ffffff</color>
    <color name="ripple_material_light">#1f000000</color>
    <color name="secondary_text_default_material_dark">#b3ffffff</color>
    <color name="secondary_text_default_material_light">#8a000000</color>
    <color name="secondary_text_disabled_material_dark">#36ffffff</color>
    <color name="secondary_text_disabled_material_light">#24000000</color>
    <color name="switch_thumb_disabled_material_dark">#ff616161</color>
    <color name="switch_thumb_disabled_material_light">#ffbdbdbd</color>
    <color name="switch_thumb_normal_material_dark">#ffbdbdbd</color>
    <color name="switch_thumb_normal_material_light">#fff1f1f1</color>
    <declare-styleable name="ActionBar"><attr name="navigationMode"><enum name="normal" value="0"/><enum name="listMode" value="1"/><enum name="tabMode" value="2"/></attr><attr name="displayOptions"><flag name="none" value="0"/><flag name="useLogo" value="0x1"/><flag name="showHome" value="0x2"/><flag name="homeAsUp" value="0x4"/><flag name="showTitle" value="0x8"/><flag name="showCustom" value="0x10"/><flag name="disableHome" value="0x20"/></attr><attr name="title"/><attr format="string" name="subtitle"/><attr format="reference" name="titleTextStyle"/><attr format="reference" name="subtitleTextStyle"/><attr format="reference" name="icon"/><attr format="reference" name="logo"/><attr format="reference" name="divider"/><attr format="reference" name="background"/><attr format="reference|color" name="backgroundStacked"/><attr format="reference|color" name="backgroundSplit"/><attr format="reference" name="customNavigationLayout"/><attr name="height"/><attr format="reference" name="homeLayout"/><attr format="reference" name="progressBarStyle"/><attr format="reference" name="indeterminateProgressStyle"/><attr format="dimension" name="progressBarPadding"/><attr name="homeAsUpIndicator"/><attr format="dimension" name="itemPadding"/><attr format="boolean" name="hideOnContentScroll"/><attr format="dimension" name="contentInsetStart"/><attr format="dimension" name="contentInsetEnd"/><attr format="dimension" name="contentInsetLeft"/><attr format="dimension" name="contentInsetRight"/><attr format="dimension" name="elevation"/><attr format="reference" name="popupTheme"/></declare-styleable>
    <declare-styleable name="ActionBarLayout"><attr name="android:layout_gravity"/></declare-styleable>
    <declare-styleable name="ActionMenuItemView"><attr name="android:minWidth"/></declare-styleable>
    <declare-styleable name="ActionMenuView"/>
    <declare-styleable name="ActionMode"><attr name="titleTextStyle"/><attr name="subtitleTextStyle"/><attr name="background"/><attr name="backgroundSplit"/><attr name="height"/><attr format="reference" name="closeItemLayout"/></declare-styleable>
    <declare-styleable name="ActivityChooserView"><attr format="string" name="initialActivityCount"/><attr format="reference" name="expandActivityOverflowButtonDrawable"/></declare-styleable>
    <declare-styleable name="AlertDialog"><attr name="android:layout"/><attr format="reference" name="buttonPanelSideLayout"/><attr format="reference" name="listLayout"/><attr format="reference" name="multiChoiceItemLayout"/><attr format="reference" name="singleChoiceItemLayout"/><attr format="reference" name="listItemLayout"/></declare-styleable>
    <declare-styleable name="AppCompatImageView"><attr name="android:src"/><attr format="reference" name="srcCompat"/></declare-styleable>
    <declare-styleable name="AppCompatTextView"><attr format="reference|boolean" name="textAllCaps"/><attr name="android:textAppearance"/></declare-styleable>
    <declare-styleable name="AppCompatTheme"><attr format="boolean" name="windowActionBar"/><attr format="boolean" name="windowNoTitle"/><attr format="boolean" name="windowActionBarOverlay"/><attr format="boolean" name="windowActionModeOverlay"/><attr format="dimension|fraction" name="windowFixedWidthMajor"/><attr format="dimension|fraction" name="windowFixedHeightMinor"/><attr format="dimension|fraction" name="windowFixedWidthMinor"/><attr format="dimension|fraction" name="windowFixedHeightMajor"/><attr format="dimension|fraction" name="windowMinWidthMajor"/><attr format="dimension|fraction" name="windowMinWidthMinor"/><attr name="android:windowIsFloating"/><attr name="android:windowAnimationStyle"/><attr format="reference" name="actionBarTabStyle"/><attr format="reference" name="actionBarTabBarStyle"/><attr format="reference" name="actionBarTabTextStyle"/><attr format="reference" name="actionOverflowButtonStyle"/><attr format="reference" name="actionOverflowMenuStyle"/><attr format="reference" name="actionBarPopupTheme"/><attr format="reference" name="actionBarStyle"/><attr format="reference" name="actionBarSplitStyle"/><attr format="reference" name="actionBarTheme"/><attr format="reference" name="actionBarWidgetTheme"/><attr format="dimension" name="actionBarSize"><enum name="wrap_content" value="0"/></attr><attr format="reference" name="actionBarDivider"/><attr format="reference" name="actionBarItemBackground"/><attr format="reference" name="actionMenuTextAppearance"/><attr format="color|reference" name="actionMenuTextColor"/><attr format="reference" name="actionModeStyle"/><attr format="reference" name="actionModeCloseButtonStyle"/><attr format="reference" name="actionModeBackground"/><attr format="reference" name="actionModeSplitBackground"/><attr format="reference" name="actionModeCloseDrawable"/><attr format="reference" name="actionModeCutDrawable"/><attr format="reference" name="actionModeCopyDrawable"/><attr format="reference" name="actionModePasteDrawable"/><attr format="reference" name="actionModeSelectAllDrawable"/><attr format="reference" name="actionModeShareDrawable"/><attr format="reference" name="actionModeFindDrawable"/><attr format="reference" name="actionModeWebSearchDrawable"/><attr format="reference" name="actionModePopupWindowStyle"/><attr format="reference" name="textAppearanceLargePopupMenu"/><attr format="reference" name="textAppearanceSmallPopupMenu"/><attr format="reference" name="dialogTheme"/><attr format="dimension" name="dialogPreferredPadding"/><attr format="reference" name="listDividerAlertDialog"/><attr format="reference" name="actionDropDownStyle"/><attr format="dimension" name="dropdownListPreferredItemHeight"/><attr format="reference" name="spinnerDropDownItemStyle"/><attr format="reference" name="homeAsUpIndicator"/><attr format="reference" name="actionButtonStyle"/><attr format="reference" name="buttonBarStyle"/><attr format="reference" name="buttonBarButtonStyle"/><attr format="reference" name="selectableItemBackground"/><attr format="reference" name="selectableItemBackgroundBorderless"/><attr format="reference" name="borderlessButtonStyle"/><attr format="reference" name="dividerVertical"/><attr format="reference" name="dividerHorizontal"/><attr format="reference" name="activityChooserViewStyle"/><attr format="reference" name="toolbarStyle"/><attr format="reference" name="toolbarNavigationButtonStyle"/><attr format="reference" name="popupMenuStyle"/><attr format="reference" name="popupWindowStyle"/><attr format="reference|color" name="editTextColor"/><attr format="reference" name="editTextBackground"/><attr format="reference" name="imageButtonStyle"/><attr format="reference" name="textAppearanceSearchResultTitle"/><attr format="reference" name="textAppearanceSearchResultSubtitle"/><attr format="reference|color" name="textColorSearchUrl"/><attr format="reference" name="searchViewStyle"/><attr format="dimension" name="listPreferredItemHeight"/><attr format="dimension" name="listPreferredItemHeightSmall"/><attr format="dimension" name="listPreferredItemHeightLarge"/><attr format="dimension" name="listPreferredItemPaddingLeft"/><attr format="dimension" name="listPreferredItemPaddingRight"/><attr format="reference" name="dropDownListViewStyle"/><attr format="reference" name="listPopupWindowStyle"/><attr format="reference" name="textAppearanceListItem"/><attr format="reference" name="textAppearanceListItemSmall"/><attr format="reference" name="panelBackground"/><attr format="dimension" name="panelMenuListWidth"/><attr format="reference" name="panelMenuListTheme"/><attr format="reference" name="listChoiceBackgroundIndicator"/><attr format="color" name="colorPrimary"/><attr format="color" name="colorPrimaryDark"/><attr format="color" name="colorAccent"/><attr format="color" name="colorControlNormal"/><attr format="color" name="colorControlActivated"/><attr format="color" name="colorControlHighlight"/><attr format="color" name="colorButtonNormal"/><attr format="color" name="colorSwitchThumbNormal"/><attr format="reference" name="controlBackground"/><attr format="reference" name="alertDialogStyle"/><attr format="reference" name="alertDialogButtonGroupStyle"/><attr format="boolean" name="alertDialogCenterButtons"/><attr format="reference" name="alertDialogTheme"/><attr format="reference|color" name="textColorAlertDialogListItem"/><attr format="reference" name="buttonBarPositiveButtonStyle"/><attr format="reference" name="buttonBarNegativeButtonStyle"/><attr format="reference" name="buttonBarNeutralButtonStyle"/><attr format="reference" name="autoCompleteTextViewStyle"/><attr format="reference" name="buttonStyle"/><attr format="reference" name="buttonStyleSmall"/><attr format="reference" name="checkboxStyle"/><attr format="reference" name="checkedTextViewStyle"/><attr format="reference" name="editTextStyle"/><attr format="reference" name="radioButtonStyle"/><attr format="reference" name="ratingBarStyle"/><attr format="reference" name="ratingBarStyleIndicator"/><attr format="reference" name="ratingBarStyleSmall"/><attr format="reference" name="seekBarStyle"/><attr format="reference" name="spinnerStyle"/><attr format="reference" name="switchStyle"/></declare-styleable>
    <declare-styleable name="ButtonBarLayout"><attr format="boolean" name="allowStacking"/></declare-styleable>
    <declare-styleable name="CompoundButton"><attr name="android:button"/><attr format="color" name="buttonTint"/><attr name="buttonTintMode"><enum name="src_over" value="3"/><enum name="src_in" value="5"/><enum name="src_atop" value="9"/><enum name="multiply" value="14"/><enum name="screen" value="15"/></attr></declare-styleable>
    <declare-styleable name="DrawerArrowToggle"><attr format="color" name="color"/><attr format="boolean" name="spinBars"/><attr format="dimension" name="drawableSize"/><attr format="dimension" name="gapBetweenBars"/><attr format="dimension" name="arrowHeadLength"/><attr format="dimension" name="arrowShaftLength"/><attr format="dimension" name="barLength"/><attr format="dimension" name="thickness"/></declare-styleable>
    <declare-styleable name="LinearLayoutCompat"><attr name="android:orientation"/><attr name="android:gravity"/><attr name="android:baselineAligned"/><attr name="android:baselineAlignedChildIndex"/><attr name="android:weightSum"/><attr format="boolean" name="measureWithLargestChild"/><attr name="divider"/><attr name="showDividers"><flag name="none" value="0"/><flag name="beginning" value="1"/><flag name="middle" value="2"/><flag name="end" value="4"/></attr><attr format="dimension" name="dividerPadding"/></declare-styleable>
    <declare-styleable name="LinearLayoutCompat_Layout"><attr name="android:layout_width"/><attr name="android:layout_height"/><attr name="android:layout_weight"/><attr name="android:layout_gravity"/></declare-styleable>
    <declare-styleable name="ListPopupWindow"><attr name="android:dropDownVerticalOffset"/><attr name="android:dropDownHorizontalOffset"/></declare-styleable>
    <declare-styleable name="MenuGroup"><attr name="android:id"/><attr name="android:menuCategory"/><attr name="android:orderInCategory"/><attr name="android:checkableBehavior"/><attr name="android:visible"/><attr name="android:enabled"/></declare-styleable>
    <declare-styleable name="MenuItem"><attr name="android:id"/><attr name="android:menuCategory"/><attr name="android:orderInCategory"/><attr name="android:title"/><attr name="android:titleCondensed"/><attr name="android:icon"/><attr name="android:alphabeticShortcut"/><attr name="android:numericShortcut"/><attr name="android:checkable"/><attr name="android:checked"/><attr name="android:visible"/><attr name="android:enabled"/><attr name="android:onClick"/><attr name="showAsAction"><flag name="never" value="0"/><flag name="ifRoom" value="1"/><flag name="always" value="2"/><flag name="withText" value="4"/><flag name="collapseActionView" value="8"/></attr><attr format="reference" name="actionLayout"/><attr format="string" name="actionViewClass"/><attr format="string" name="actionProviderClass"/></declare-styleable>
    <declare-styleable name="MenuView"><attr name="android:itemTextAppearance"/><attr name="android:horizontalDivider"/><attr name="android:verticalDivider"/><attr name="android:headerBackground"/><attr name="android:itemBackground"/><attr name="android:windowAnimationStyle"/><attr name="android:itemIconDisabledAlpha"/><attr format="boolean" name="preserveIconSpacing"/></declare-styleable>
    <declare-styleable name="PopupWindow"><attr format="boolean" name="overlapAnchor"/><attr name="android:popupBackground"/></declare-styleable>
    <declare-styleable name="PopupWindowBackgroundState"><attr format="boolean" name="state_above_anchor"/></declare-styleable>
    <declare-styleable name="SearchView"><attr format="reference" name="layout"/><attr format="boolean" name="iconifiedByDefault"/><attr name="android:maxWidth"/><attr format="string" name="queryHint"/><attr format="string" name="defaultQueryHint"/><attr name="android:imeOptions"/><attr name="android:inputType"/><attr format="reference" name="closeIcon"/><attr format="reference" name="goIcon"/><attr format="reference" name="searchIcon"/><attr format="reference" name="searchHintIcon"/><attr format="reference" name="voiceIcon"/><attr format="reference" name="commitIcon"/><attr format="reference" name="suggestionRowLayout"/><attr format="reference" name="queryBackground"/><attr format="reference" name="submitBackground"/><attr name="android:focusable"/></declare-styleable>
    <declare-styleable name="Spinner"><attr name="android:prompt"/><attr name="popupTheme"/><attr name="android:popupBackground"/><attr name="android:dropDownWidth"/><attr name="android:entries"/></declare-styleable>
    <declare-styleable name="SwitchCompat"><attr name="android:thumb"/><attr format="reference" name="track"/><attr name="android:textOn"/><attr name="android:textOff"/><attr format="dimension" name="thumbTextPadding"/><attr format="reference" name="switchTextAppearance"/><attr format="dimension" name="switchMinWidth"/><attr format="dimension" name="switchPadding"/><attr format="boolean" name="splitTrack"/><attr format="boolean" name="showText"/></declare-styleable>
    <declare-styleable name="TextAppearance"><attr name="android:textSize"/><attr name="android:textColor"/><attr name="android:textStyle"/><attr name="android:typeface"/><attr name="textAllCaps"/><attr name="android:shadowColor"/><attr name="android:shadowDy"/><attr name="android:shadowDx"/><attr name="android:shadowRadius"/></declare-styleable>
    <declare-styleable name="Toolbar"><attr format="reference" name="titleTextAppearance"/><attr format="reference" name="subtitleTextAppearance"/><attr name="title"/><attr name="subtitle"/><attr name="android:gravity"/><attr format="dimension" name="titleMargins"/><attr format="dimension" name="titleMarginStart"/><attr format="dimension" name="titleMarginEnd"/><attr format="dimension" name="titleMarginTop"/><attr format="dimension" name="titleMarginBottom"/><attr name="contentInsetStart"/><attr name="contentInsetEnd"/><attr name="contentInsetLeft"/><attr name="contentInsetRight"/><attr format="dimension" name="maxButtonHeight"/><attr format="reference" name="collapseIcon"/><attr format="string" name="collapseContentDescription"/><attr name="popupTheme"/><attr format="reference" name="navigationIcon"/><attr format="string" name="navigationContentDescription"/><attr name="android:minHeight"/><attr name="logo"/><attr format="string" name="logoDescription"/><attr format="color" name="titleTextColor"/><attr format="color" name="subtitleTextColor"/></declare-styleable>
    <declare-styleable name="View"><attr format="dimension" name="paddingStart"/><attr format="dimension" name="paddingEnd"/><attr name="android:focusable"/><attr format="reference" name="theme"/><attr name="android:theme"/></declare-styleable>
    <declare-styleable name="ViewBackgroundHelper"><attr name="android:background"/><attr format="color" name="backgroundTint"/><attr name="backgroundTintMode"><enum name="src_over" value="3"/><enum name="src_in" value="5"/><enum name="src_atop" value="9"/><enum name="multiply" value="14"/><enum name="screen" value="15"/></attr></declare-styleable>
    <declare-styleable name="ViewStubCompat"><attr name="android:layout"/><attr name="android:inflatedId"/><attr name="android:id"/></declare-styleable>
    <dimen name="abc_action_bar_content_inset_material">16dp</dimen>
    <dimen name="abc_action_bar_default_height_material">56dp</dimen>
    <dimen name="abc_action_bar_default_padding_end_material">0dp</dimen>
    <dimen name="abc_action_bar_default_padding_start_material">0dp</dimen>
    <dimen name="abc_action_bar_icon_vertical_padding_material">16dp</dimen>
    <dimen name="abc_action_bar_overflow_padding_end_material">10dp</dimen>
    <dimen name="abc_action_bar_overflow_padding_start_material">6dp</dimen>
    <dimen name="abc_action_bar_progress_bar_size">40dp</dimen>
    <dimen name="abc_action_bar_stacked_max_height">48dp</dimen>
    <dimen name="abc_action_bar_stacked_tab_max_width">180dp</dimen>
    <dimen name="abc_action_bar_subtitle_bottom_margin_material">5dp</dimen>
    <dimen name="abc_action_bar_subtitle_top_margin_material">-3dp</dimen>
    <dimen name="abc_action_button_min_height_material">48dp</dimen>
    <dimen name="abc_action_button_min_width_material">48dp</dimen>
    <dimen name="abc_action_button_min_width_overflow_material">36dp</dimen>
    <dimen name="abc_alert_dialog_button_bar_height">48dp</dimen>
    <dimen name="abc_button_inset_horizontal_material">@dimen/abc_control_inset_material</dimen>
    <dimen name="abc_button_inset_vertical_material">6dp</dimen>
    <dimen name="abc_button_padding_horizontal_material">8dp</dimen>
    <dimen name="abc_button_padding_vertical_material">@dimen/abc_control_padding_material</dimen>
    <dimen name="abc_config_prefDialogWidth">320dp</dimen>
    <dimen name="abc_control_corner_material">2dp</dimen>
    <dimen name="abc_control_inset_material">4dp</dimen>
    <dimen name="abc_control_padding_material">4dp</dimen>
    <item name="abc_dialog_fixed_height_major" type="dimen">80%</item>
    <item name="abc_dialog_fixed_height_minor" type="dimen">100%</item>
    <item name="abc_dialog_fixed_width_major" type="dimen">320dp</item>
    <item name="abc_dialog_fixed_width_minor" type="dimen">320dp</item>
    <dimen name="abc_dialog_list_padding_vertical_material">8dp</dimen>
    <item name="abc_dialog_min_width_major" type="dimen">65%</item>
    <item name="abc_dialog_min_width_minor" type="dimen">95%</item>
    <dimen name="abc_dialog_padding_material">24dp</dimen>
    <dimen name="abc_dialog_padding_top_material">18dp</dimen>
    <item format="float" name="abc_disabled_alpha_material_dark" type="dimen">0.30</item>
    <item format="float" name="abc_disabled_alpha_material_light" type="dimen">0.26</item>
    <dimen name="abc_dropdownitem_icon_width">32dip</dimen>
    <dimen name="abc_dropdownitem_text_padding_left">8dip</dimen>
    <dimen name="abc_dropdownitem_text_padding_right">8dip</dimen>
    <dimen name="abc_edit_text_inset_bottom_material">7dp</dimen>
    <dimen name="abc_edit_text_inset_horizontal_material">4dp</dimen>
    <dimen name="abc_edit_text_inset_top_material">10dp</dimen>
    <dimen name="abc_floating_window_z">16dp</dimen>
    <dimen name="abc_list_item_padding_horizontal_material">@dimen/abc_action_bar_content_inset_material</dimen>
    <dimen name="abc_panel_menu_list_width">296dp</dimen>
    <dimen name="abc_search_view_preferred_width">320dip</dimen>
    <dimen name="abc_search_view_text_min_width">160dip</dimen>
    <dimen name="abc_seekbar_track_background_height_material">2dp</dimen>
    <dimen name="abc_seekbar_track_progress_height_material">2dp</dimen>
    <dimen name="abc_select_dialog_padding_start_material">20dp</dimen>
    <dimen name="abc_switch_padding">3dp</dimen>
    <dimen name="abc_text_size_body_1_material">14sp</dimen>
    <dimen name="abc_text_size_body_2_material">14sp</dimen>
    <dimen name="abc_text_size_button_material">14sp</dimen>
    <dimen name="abc_text_size_caption_material">12sp</dimen>
    <dimen name="abc_text_size_display_1_material">34sp</dimen>
    <dimen name="abc_text_size_display_2_material">45sp</dimen>
    <dimen name="abc_text_size_display_3_material">56sp</dimen>
    <dimen name="abc_text_size_display_4_material">112sp</dimen>
    <dimen name="abc_text_size_headline_material">24sp</dimen>
    <dimen name="abc_text_size_large_material">22sp</dimen>
    <dimen name="abc_text_size_medium_material">18sp</dimen>
    <dimen name="abc_text_size_menu_material">16sp</dimen>
    <dimen name="abc_text_size_small_material">14sp</dimen>
    <dimen name="abc_text_size_subhead_material">16sp</dimen>
    <dimen name="abc_text_size_subtitle_material_toolbar">16dp</dimen>
    <dimen name="abc_text_size_title_material">20sp</dimen>
    <dimen name="abc_text_size_title_material_toolbar">20dp</dimen>
    <item format="float" name="disabled_alpha_material_dark" type="dimen">0.30</item>
    <item format="float" name="disabled_alpha_material_light" type="dimen">0.26</item>
    <item format="float" name="highlight_alpha_material_colored" type="dimen">0.26</item>
    <item format="float" name="highlight_alpha_material_dark" type="dimen">0.20</item>
    <item format="float" name="highlight_alpha_material_light" type="dimen">0.12</item>
    <dimen name="notification_large_icon_height">64dp</dimen>
    <dimen name="notification_large_icon_width">64dp</dimen>
    <dimen name="notification_subtext_size">12dp</dimen>
    <drawable name="notification_template_icon_bg">#3333B5E5</drawable>
    <item name="action_bar_activity_content" type="id"/>
    <item name="action_bar_spinner" type="id"/>
    <item name="action_menu_divider" type="id"/>
    <item name="action_menu_presenter" type="id"/>
    <item name="home" type="id"/>
    <item name="progress_circular" type="id"/>
    <item name="progress_horizontal" type="id"/>
    <item name="split_action_bar" type="id"/>
    <item name="up" type="id"/>
    <integer name="abc_config_activityDefaultDur">220</integer>
    <integer name="abc_config_activityShortDur">150</integer>
    <integer name="abc_max_action_buttons">2</integer>
    <integer name="cancel_button_image_alpha">127</integer>
    <integer name="status_bar_notification_info_maxnum">999</integer>
    <string name="abc_action_bar_home_description">Navigate home</string>
    <string name="abc_action_bar_home_description_format">%1$s, %2$s</string>
    <string name="abc_action_bar_home_subtitle_description_format">%1$s, %2$s, %3$s</string>
    <string name="abc_action_bar_up_description">Navigate up</string>
    <string name="abc_action_menu_overflow_description">More options</string>
    <string name="abc_action_mode_done">Done</string>
    <string name="abc_activity_chooser_view_see_all">See all</string>
    <string name="abc_activitychooserview_choose_application">Choose an app</string>
    <string name="abc_capital_off">OFF</string>
    <string name="abc_capital_on">ON</string>
    <string name="abc_search_hint">Search…</string>
    <string name="abc_searchview_description_clear">Clear query</string>
    <string name="abc_searchview_description_query">Search query</string>
    <string name="abc_searchview_description_search">Search</string>
    <string name="abc_searchview_description_submit">Submit query</string>
    <string name="abc_searchview_description_voice">Voice search</string>
    <string name="abc_shareactionprovider_share_with">Share with</string>
    <string name="abc_shareactionprovider_share_with_application">Share with %s</string>
    <string name="abc_toolbar_collapse_description">Collapse</string>
    <string name="status_bar_notification_info_overflow">999+</string>
    <style name="AlertDialog.AppCompat" parent="Base.AlertDialog.AppCompat"/>
    <style name="AlertDialog.AppCompat.Light" parent="Base.AlertDialog.AppCompat.Light"/>
    <style name="Animation.AppCompat.Dialog" parent="Base.Animation.AppCompat.Dialog"/>
    <style name="Animation.AppCompat.DropDownUp" parent="Base.Animation.AppCompat.DropDownUp"/>
    <style name="Base.AlertDialog.AppCompat" parent="android:Widget">
        <item name="android:layout">@layout/abc_alert_dialog_material</item>
        <item name="listLayout">@layout/abc_select_dialog_material</item>
        <item name="listItemLayout">@layout/select_dialog_item_material</item>
        <item name="multiChoiceItemLayout">@layout/select_dialog_multichoice_material</item>
        <item name="singleChoiceItemLayout">@layout/select_dialog_singlechoice_material</item>
    </style>
    <style name="Base.AlertDialog.AppCompat.Light" parent="Base.AlertDialog.AppCompat"/>
    <style name="Base.Animation.AppCompat.Dialog" parent="android:Animation">
        <item name="android:windowEnterAnimation">@anim/abc_popup_enter</item>
        <item name="android:windowExitAnimation">@anim/abc_popup_exit</item>
    </style>
    <style name="Base.Animation.AppCompat.DropDownUp" parent="android:Animation">
        <item name="android:windowEnterAnimation">@anim/abc_grow_fade_in_from_bottom</item>
        <item name="android:windowExitAnimation">@anim/abc_shrink_fade_out_from_bottom</item>
    </style>
    <style name="Base.DialogWindowTitle.AppCompat" parent="android:Widget">
        <item name="android:maxLines">1</item>
        <item name="android:scrollHorizontally">true</item>
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Title</item>
    </style>
    <style name="Base.DialogWindowTitleBackground.AppCompat" parent="android:Widget">
        <item name="android:background">@null</item>
        <item name="android:paddingLeft">?attr/dialogPreferredPadding</item>
        <item name="android:paddingRight">?attr/dialogPreferredPadding</item>
        <item name="android:paddingTop">@dimen/abc_dialog_padding_top_material</item>
    </style>
    <style name="Base.TextAppearance.AppCompat" parent="android:TextAppearance">
        <item name="android:textColor">?android:textColorPrimary</item>
        <item name="android:textColorHint">?android:textColorHint</item>
        <item name="android:textColorHighlight">?android:textColorHighlight</item>
        <item name="android:textColorLink">?android:textColorLink</item>
        <item name="android:textSize">@dimen/abc_text_size_body_1_material</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Body1">
        <item name="android:textSize">@dimen/abc_text_size_body_1_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Body2">
        <item name="android:textSize">@dimen/abc_text_size_body_2_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Button">
        <item name="android:textSize">@dimen/abc_text_size_button_material</item>
        <item name="textAllCaps">true</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Caption">
        <item name="android:textSize">@dimen/abc_text_size_caption_material</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Display1">
        <item name="android:textSize">@dimen/abc_text_size_display_1_material</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Display2">
        <item name="android:textSize">@dimen/abc_text_size_display_2_material</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Display3">
        <item name="android:textSize">@dimen/abc_text_size_display_3_material</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Display4">
        <item name="android:textSize">@dimen/abc_text_size_display_4_material</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Headline">
        <item name="android:textSize">@dimen/abc_text_size_headline_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Inverse">
        <item name="android:textColor">?android:attr/textColorPrimaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Large">
        <item name="android:textSize">@dimen/abc_text_size_large_material</item>
        <item name="android:textColor">?android:attr/textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Large.Inverse">
        <item name="android:textColor">?android:attr/textColorPrimaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Light.Widget.PopupMenu.Large" parent="TextAppearance.AppCompat.Menu">
    </style>
    <style name="Base.TextAppearance.AppCompat.Light.Widget.PopupMenu.Small" parent="TextAppearance.AppCompat.Menu">
    </style>
    <style name="Base.TextAppearance.AppCompat.Medium">
        <item name="android:textSize">@dimen/abc_text_size_medium_material</item>
        <item name="android:textColor">?android:attr/textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Medium.Inverse">
        <item name="android:textColor">?android:attr/textColorSecondaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Menu">
        <item name="android:textSize">@dimen/abc_text_size_menu_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.SearchResult" parent="">
        <item name="android:textStyle">normal</item>
        <item name="android:textColor">?android:textColorPrimary</item>
        <item name="android:textColorHint">?android:textColorHint</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.SearchResult.Subtitle">
        <item name="android:textSize">14sp</item>
        <item name="android:textColor">?android:textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.SearchResult.Title">
        <item name="android:textSize">18sp</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Small">
        <item name="android:textSize">@dimen/abc_text_size_small_material</item>
        <item name="android:textColor">?android:attr/textColorTertiary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Small.Inverse">
        <item name="android:textColor">?android:attr/textColorTertiaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Subhead">
        <item name="android:textSize">@dimen/abc_text_size_subhead_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Subhead.Inverse">
        <item name="android:textColor">?android:attr/textColorPrimaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Title">
        <item name="android:textSize">@dimen/abc_text_size_title_material</item>
        <item name="android:textColor">?android:textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Title.Inverse">
        <item name="android:textColor">?android:attr/textColorPrimaryInverse</item>
        <item name="android:textColorHint">?android:attr/textColorHintInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionBar.Menu" parent="TextAppearance.AppCompat.Button">
        <item name="android:textColor">?attr/actionMenuTextColor</item>
        <item name="textAllCaps">@bool/abc_config_actionMenuItemAllCaps</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionBar.Subtitle" parent="TextAppearance.AppCompat.Subhead">
        <item name="android:textSize">@dimen/abc_text_size_subtitle_material_toolbar</item>
        <item name="android:textColor">?android:attr/textColorSecondary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionBar.Subtitle.Inverse" parent="TextAppearance.AppCompat.Subhead.Inverse">
        <item name="android:textSize">@dimen/abc_text_size_subtitle_material_toolbar</item>
        <item name="android:textColor">?android:attr/textColorSecondaryInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionBar.Title" parent="TextAppearance.AppCompat.Title">
        <item name="android:textSize">@dimen/abc_text_size_title_material_toolbar</item>
        <item name="android:textColor">?android:attr/textColorPrimary</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionBar.Title.Inverse" parent="TextAppearance.AppCompat.Title.Inverse">
        <item name="android:textSize">@dimen/abc_text_size_title_material_toolbar</item>
        <item name="android:textColor">?android:attr/textColorPrimaryInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionMode.Subtitle" parent="TextAppearance.AppCompat.Widget.ActionBar.Subtitle"/>
    <style name="Base.TextAppearance.AppCompat.Widget.ActionMode.Title" parent="TextAppearance.AppCompat.Widget.ActionBar.Title"/>
    <style name="Base.TextAppearance.AppCompat.Widget.Button" parent="TextAppearance.AppCompat.Button"/>
    <style name="Base.TextAppearance.AppCompat.Widget.Button.Inverse" parent="TextAppearance.AppCompat.Button">
        <item name="android:textColor">?android:textColorPrimaryInverse</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.DropDownItem" parent="android:TextAppearance.Small">
        <item name="android:textColor">?android:attr/textColorPrimaryDisableOnly</item>
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.PopupMenu.Large" parent="TextAppearance.AppCompat.Menu">
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.PopupMenu.Small" parent="TextAppearance.AppCompat.Menu">
    </style>
    <style name="Base.TextAppearance.AppCompat.Widget.Switch" parent="TextAppearance.AppCompat.Button"/>
    <style name="Base.TextAppearance.AppCompat.Widget.TextView.SpinnerItem" parent="TextAppearance.AppCompat.Menu"/>
    <style name="Base.TextAppearance.Widget.AppCompat.ExpandedMenu.Item" parent="android:TextAppearance.Medium">
        <item name="android:textColor">?android:attr/textColorPrimaryDisableOnly</item>
    </style>
    <style name="Base.TextAppearance.Widget.AppCompat.Toolbar.Subtitle" parent="TextAppearance.AppCompat.Widget.ActionBar.Subtitle">
    </style>
    <style name="Base.TextAppearance.Widget.AppCompat.Toolbar.Title" parent="TextAppearance.AppCompat.Widget.ActionBar.Title">
    </style>
    <style name="Base.Theme.AppCompat" parent="Base.V7.Theme.AppCompat">
    </style>
    <style name="Base.Theme.AppCompat.CompactMenu" parent="">
        <item name="android:itemTextAppearance">?android:attr/textAppearanceMedium</item>
        <item name="android:listViewStyle">@style/Widget.AppCompat.ListView.Menu</item>
        <item name="android:windowAnimationStyle">@style/Animation.AppCompat.DropDownUp</item>
    </style>
    <style name="Base.Theme.AppCompat.Dialog" parent="Base.V7.Theme.AppCompat.Dialog"/>
    <style name="Base.Theme.AppCompat.Dialog.Alert">
        <item name="windowMinWidthMajor">@dimen/abc_dialog_min_width_major</item>
        <item name="windowMinWidthMinor">@dimen/abc_dialog_min_width_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.Dialog.FixedSize">
        <item name="windowFixedWidthMajor">@dimen/abc_dialog_fixed_width_major</item>
        <item name="windowFixedWidthMinor">@dimen/abc_dialog_fixed_width_minor</item>
        <item name="windowFixedHeightMajor">@dimen/abc_dialog_fixed_height_major</item>
        <item name="windowFixedHeightMinor">@dimen/abc_dialog_fixed_height_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.Dialog.MinWidth">
        <item name="windowMinWidthMajor">@dimen/abc_dialog_min_width_major</item>
        <item name="windowMinWidthMinor">@dimen/abc_dialog_min_width_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.DialogWhenLarge" parent="Theme.AppCompat"/>
    <style name="Base.Theme.AppCompat.Light" parent="Base.V7.Theme.AppCompat.Light">
    </style>
    <style name="Base.Theme.AppCompat.Light.DarkActionBar" parent="Base.Theme.AppCompat.Light">
        <item name="actionBarPopupTheme">@style/ThemeOverlay.AppCompat.Light</item>
        <item name="actionBarWidgetTheme">@null</item>
        <item name="actionBarTheme">@style/ThemeOverlay.AppCompat.Dark.ActionBar</item>

        <!-- Panel attributes -->
        <item name="listChoiceBackgroundIndicator">@drawable/abc_list_selector_holo_dark</item>

        <item name="colorPrimaryDark">@color/primary_dark_material_dark</item>
        <item name="colorPrimary">@color/primary_material_dark</item>
    </style>
    <style name="Base.Theme.AppCompat.Light.Dialog" parent="Base.V7.Theme.AppCompat.Light.Dialog"/>
    <style name="Base.Theme.AppCompat.Light.Dialog.Alert">
        <item name="windowMinWidthMajor">@dimen/abc_dialog_min_width_major</item>
        <item name="windowMinWidthMinor">@dimen/abc_dialog_min_width_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.Light.Dialog.FixedSize">
        <item name="windowFixedWidthMajor">@dimen/abc_dialog_fixed_width_major</item>
        <item name="windowFixedWidthMinor">@dimen/abc_dialog_fixed_width_minor</item>
        <item name="windowFixedHeightMajor">@dimen/abc_dialog_fixed_height_major</item>
        <item name="windowFixedHeightMinor">@dimen/abc_dialog_fixed_height_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.Light.Dialog.MinWidth">
        <item name="windowMinWidthMajor">@dimen/abc_dialog_min_width_major</item>
        <item name="windowMinWidthMinor">@dimen/abc_dialog_min_width_minor</item>
    </style>
    <style name="Base.Theme.AppCompat.Light.DialogWhenLarge" parent="Theme.AppCompat.Light"/>
    <style name="Base.ThemeOverlay.AppCompat" parent="Platform.ThemeOverlay.AppCompat"/>
    <style name="Base.ThemeOverlay.AppCompat.ActionBar">
        <item name="colorControlNormal">?android:attr/textColorPrimary</item>
        <item name="searchViewStyle">@style/Widget.AppCompat.SearchView.ActionBar</item>
    </style>
    <style name="Base.ThemeOverlay.AppCompat.Dark" parent="Platform.ThemeOverlay.AppCompat.Dark">
        <item name="android:windowBackground">@color/background_material_dark</item>
        <item name="android:colorForeground">@color/foreground_material_dark</item>
        <item name="android:colorForegroundInverse">@color/foreground_material_light</item>
        <item name="android:colorBackground">@color/background_material_dark</item>
        <item name="android:colorBackgroundCacheHint">@color/abc_background_cache_hint_selector_material_dark</item>

        <item name="android:textColorPrimary">@color/abc_primary_text_material_dark</item>
        <item name="android:textColorPrimaryInverse">@color/abc_primary_text_material_light</item>
        <item name="android:textColorPrimaryDisableOnly">@color/abc_primary_text_disable_only_material_dark</item>
        <item name="android:textColorSecondary">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorSecondaryInverse">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorTertiary">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorTertiaryInverse">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorHint">@color/hint_foreground_material_dark</item>
        <item name="android:textColorHintInverse">@color/hint_foreground_material_light</item>
        <item name="android:textColorHighlight">@color/highlighted_text_material_dark</item>

        <item name="colorControlNormal">?android:attr/textColorSecondary</item>
        <item name="colorControlHighlight">@color/ripple_material_dark</item>
        <item name="colorButtonNormal">@color/button_material_dark</item>
        <item name="colorSwitchThumbNormal">@color/switch_thumb_material_dark</item>

        <!-- Used by MediaRouter -->
        <item name="isLightTheme">false</item>
    </style>
    <style name="Base.ThemeOverlay.AppCompat.Dark.ActionBar">
        <item name="colorControlNormal">?android:attr/textColorPrimary</item>
        <item name="searchViewStyle">@style/Widget.AppCompat.SearchView.ActionBar</item>
    </style>
    <style name="Base.ThemeOverlay.AppCompat.Light" parent="Platform.ThemeOverlay.AppCompat.Light">
        <item name="android:windowBackground">@color/background_material_light</item>
        <item name="android:colorForeground">@color/foreground_material_light</item>
        <item name="android:colorForegroundInverse">@color/foreground_material_dark</item>
        <item name="android:colorBackground">@color/background_material_light</item>
        <item name="android:colorBackgroundCacheHint">@color/abc_background_cache_hint_selector_material_light</item>

        <item name="android:textColorPrimary">@color/abc_primary_text_material_light</item>
        <item name="android:textColorPrimaryInverse">@color/abc_primary_text_material_dark</item>
        <item name="android:textColorSecondary">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorSecondaryInverse">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorTertiary">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorTertiaryInverse">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorPrimaryDisableOnly">@color/abc_primary_text_disable_only_material_light</item>
        <item name="android:textColorPrimaryInverseDisableOnly">@color/abc_primary_text_disable_only_material_dark</item>
        <item name="android:textColorHint">@color/hint_foreground_material_light</item>
        <item name="android:textColorHintInverse">@color/hint_foreground_material_dark</item>
        <item name="android:textColorHighlight">@color/highlighted_text_material_light</item>

        <item name="colorControlNormal">?android:attr/textColorSecondary</item>
        <item name="colorControlHighlight">@color/ripple_material_light</item>
        <item name="colorButtonNormal">@color/button_material_light</item>
        <item name="colorSwitchThumbNormal">@color/switch_thumb_material_light</item>

        <!-- Used by MediaRouter -->
        <item name="isLightTheme">true</item>
    </style>
    <style name="Base.V7.Theme.AppCompat" parent="Platform.AppCompat">
        <item name="windowNoTitle">false</item>
        <item name="windowActionBar">true</item>
        <item name="windowActionBarOverlay">false</item>
        <item name="windowActionModeOverlay">false</item>
        <item name="actionBarPopupTheme">@null</item>

        <!-- Used by MediaRouter -->
        <item name="isLightTheme">false</item>

        <item name="selectableItemBackground">@drawable/abc_item_background_holo_dark</item>
        <item name="selectableItemBackgroundBorderless">?attr/selectableItemBackground</item>
        <item name="borderlessButtonStyle">@style/Widget.AppCompat.Button.Borderless</item>
        <item name="homeAsUpIndicator">@drawable/abc_ic_ab_back_mtrl_am_alpha</item>

        <item name="dividerVertical">@drawable/abc_list_divider_mtrl_alpha</item>
        <item name="dividerHorizontal">@drawable/abc_list_divider_mtrl_alpha</item>

        <!-- Action Bar Styles -->
        <item name="actionBarTabStyle">@style/Widget.AppCompat.ActionBar.TabView</item>
        <item name="actionBarTabBarStyle">@style/Widget.AppCompat.ActionBar.TabBar</item>
        <item name="actionBarTabTextStyle">@style/Widget.AppCompat.ActionBar.TabText</item>
        <item name="actionButtonStyle">@style/Widget.AppCompat.ActionButton</item>
        <item name="actionOverflowButtonStyle">@style/Widget.AppCompat.ActionButton.Overflow</item>
        <item name="actionOverflowMenuStyle">@style/Widget.AppCompat.PopupMenu.Overflow</item>
        <item name="actionBarStyle">@style/Widget.AppCompat.ActionBar.Solid</item>
        <item name="actionBarSplitStyle">?attr/actionBarStyle</item>
        <item name="actionBarWidgetTheme">@null</item>
        <item name="actionBarTheme">@style/ThemeOverlay.AppCompat.ActionBar</item>
        <item name="actionBarSize">@dimen/abc_action_bar_default_height_material</item>
        <item name="actionBarDivider">?attr/dividerVertical</item>
        <item name="actionBarItemBackground">?attr/selectableItemBackgroundBorderless</item>
        <item name="actionMenuTextAppearance">@style/TextAppearance.AppCompat.Widget.ActionBar.Menu</item>
        <item name="actionMenuTextColor">?android:attr/textColorPrimaryDisableOnly</item>

        <!-- Dropdown Spinner Attributes -->
        <item name="actionDropDownStyle">@style/Widget.AppCompat.Spinner.DropDown.ActionBar</item>

        <!-- Action Mode -->
        <item name="actionModeStyle">@style/Widget.AppCompat.ActionMode</item>
        <item name="actionModeBackground">@drawable/abc_cab_background_top_material</item>
        <item name="actionModeSplitBackground">?attr/colorPrimaryDark</item>
        <item name="actionModeCloseDrawable">@drawable/abc_ic_ab_back_mtrl_am_alpha</item>
        <item name="actionModeCloseButtonStyle">@style/Widget.AppCompat.ActionButton.CloseMode</item>

        <item name="actionModeCutDrawable">@drawable/abc_ic_menu_cut_mtrl_alpha</item>
        <item name="actionModeCopyDrawable">@drawable/abc_ic_menu_copy_mtrl_am_alpha</item>
        <item name="actionModePasteDrawable">@drawable/abc_ic_menu_paste_mtrl_am_alpha</item>
        <item name="actionModeSelectAllDrawable">@drawable/abc_ic_menu_selectall_mtrl_alpha</item>
        <item name="actionModeShareDrawable">@drawable/abc_ic_menu_share_mtrl_alpha</item>

        <!-- Panel attributes -->
        <item name="panelMenuListWidth">@dimen/abc_panel_menu_list_width</item>
        <item name="panelMenuListTheme">@style/Theme.AppCompat.CompactMenu</item>
        <item name="panelBackground">@drawable/abc_menu_hardkey_panel_mtrl_mult</item>
        <item name="android:panelBackground">@android:color/transparent</item>
        <item name="listChoiceBackgroundIndicator">@drawable/abc_list_selector_holo_dark</item>

        <!-- List attributes -->
        <item name="textAppearanceListItem">@style/TextAppearance.AppCompat.Subhead</item>
        <item name="textAppearanceListItemSmall">@style/TextAppearance.AppCompat.Subhead</item>
        <item name="listPreferredItemHeight">64dp</item>
        <item name="listPreferredItemHeightSmall">48dp</item>
        <item name="listPreferredItemHeightLarge">80dp</item>
        <item name="listPreferredItemPaddingLeft">@dimen/abc_list_item_padding_horizontal_material</item>
        <item name="listPreferredItemPaddingRight">@dimen/abc_list_item_padding_horizontal_material</item>

        <!-- Spinner styles -->
        <item name="spinnerStyle">@style/Widget.AppCompat.Spinner</item>
        <item name="android:spinnerItemStyle">@style/Widget.AppCompat.TextView.SpinnerItem</item>
        <item name="android:dropDownListViewStyle">@style/Widget.AppCompat.ListView.DropDown</item>

        <!-- Required for use of support_simple_spinner_dropdown_item.xml -->
        <item name="spinnerDropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
        <item name="dropdownListPreferredItemHeight">?attr/listPreferredItemHeightSmall</item>

        <!-- Popup Menu styles -->
        <item name="popupMenuStyle">@style/Widget.AppCompat.PopupMenu</item>
        <item name="textAppearanceLargePopupMenu">@style/TextAppearance.AppCompat.Widget.PopupMenu.Large</item>
        <item name="textAppearanceSmallPopupMenu">@style/TextAppearance.AppCompat.Widget.PopupMenu.Small</item>
        <item name="listPopupWindowStyle">@style/Widget.AppCompat.ListPopupWindow</item>
        <item name="dropDownListViewStyle">?android:attr/dropDownListViewStyle</item>

        <!-- SearchView attributes -->
        <item name="searchViewStyle">@style/Widget.AppCompat.SearchView</item>
        <item name="android:dropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
        <item name="textColorSearchUrl">@color/abc_search_url_text</item>
        <item name="textAppearanceSearchResultTitle">@style/TextAppearance.AppCompat.SearchResult.Title</item>
        <item name="textAppearanceSearchResultSubtitle">@style/TextAppearance.AppCompat.SearchResult.Subtitle</item>

        <!-- ShareActionProvider attributes -->
        <item name="activityChooserViewStyle">@style/Widget.AppCompat.ActivityChooserView</item>

        <!-- Toolbar styles -->
        <item name="toolbarStyle">@style/Widget.AppCompat.Toolbar</item>
        <item name="toolbarNavigationButtonStyle">@style/Widget.AppCompat.Toolbar.Button.Navigation</item>

        <item name="editTextStyle">@style/Widget.AppCompat.EditText</item>
        <item name="editTextBackground">@drawable/abc_edit_text_material</item>
        <item name="editTextColor">?android:attr/textColorPrimary</item>
        <item name="autoCompleteTextViewStyle">@style/Widget.AppCompat.AutoCompleteTextView</item>

        <!-- Color palette -->
        <item name="colorPrimaryDark">@color/primary_dark_material_dark</item>
        <item name="colorPrimary">@color/primary_material_dark</item>
        <item name="colorAccent">@color/accent_material_dark</item>

        <item name="colorControlNormal">?android:attr/textColorSecondary</item>
        <item name="colorControlActivated">?attr/colorAccent</item>
        <item name="colorControlHighlight">@color/ripple_material_dark</item>
        <item name="colorButtonNormal">@color/button_material_dark</item>
        <item name="colorSwitchThumbNormal">@color/switch_thumb_material_dark</item>
        <item name="controlBackground">?attr/selectableItemBackgroundBorderless</item>

        <item name="drawerArrowStyle">@style/Widget.AppCompat.DrawerArrowToggle</item>

        <item name="checkboxStyle">@style/Widget.AppCompat.CompoundButton.CheckBox</item>
        <item name="radioButtonStyle">@style/Widget.AppCompat.CompoundButton.RadioButton</item>
        <item name="switchStyle">@style/Widget.AppCompat.CompoundButton.Switch</item>

        <item name="ratingBarStyle">@style/Widget.AppCompat.RatingBar</item>
        <item name="ratingBarStyleIndicator">@style/Widget.AppCompat.RatingBar.Indicator</item>
        <item name="ratingBarStyleSmall">@style/Widget.AppCompat.RatingBar.Small</item>
        <item name="seekBarStyle">@style/Widget.AppCompat.SeekBar</item>

        <!-- Button styles -->
        <item name="buttonStyle">@style/Widget.AppCompat.Button</item>
        <item name="buttonStyleSmall">@style/Widget.AppCompat.Button.Small</item>
        <item name="android:textAppearanceButton">@style/TextAppearance.AppCompat.Widget.Button</item>

        <item name="imageButtonStyle">@style/Widget.AppCompat.ImageButton</item>

        <item name="buttonBarStyle">@style/Widget.AppCompat.ButtonBar</item>
        <item name="buttonBarButtonStyle">@style/Widget.AppCompat.Button.ButtonBar.AlertDialog</item>
        <item name="buttonBarPositiveButtonStyle">?attr/buttonBarButtonStyle</item>
        <item name="buttonBarNegativeButtonStyle">?attr/buttonBarButtonStyle</item>
        <item name="buttonBarNeutralButtonStyle">?attr/buttonBarButtonStyle</item>

        <!-- Dialog attributes -->
        <item name="dialogTheme">@style/Theme.AppCompat.Dialog</item>
        <item name="dialogPreferredPadding">@dimen/abc_dialog_padding_material</item>

        <item name="alertDialogTheme">@style/Theme.AppCompat.Dialog.Alert</item>
        <item name="alertDialogStyle">@style/AlertDialog.AppCompat</item>
        <item name="alertDialogCenterButtons">false</item>
        <item name="textColorAlertDialogListItem">@color/abc_primary_text_material_dark</item>
        <item name="listDividerAlertDialog">@null</item>

        <!-- Define these here; ContextThemeWrappers around themes that define them should
             always clear these values. -->
        <item name="windowFixedWidthMajor">0dp</item>
        <item name="windowFixedWidthMinor">0dp</item>
        <item name="windowFixedHeightMajor">0dp</item>
        <item name="windowFixedHeightMinor">0dp</item>
    </style>
    <style name="Base.V7.Theme.AppCompat.Dialog" parent="Base.Theme.AppCompat">
        <item name="android:colorBackground">@color/background_floating_material_dark</item>
        <item name="android:colorBackgroundCacheHint">@null</item>

        <item name="android:windowFrame">@null</item>
        <item name="android:windowTitleStyle">@style/RtlOverlay.DialogWindowTitle.AppCompat</item>
        <item name="android:windowTitleBackgroundStyle">@style/Base.DialogWindowTitleBackground.AppCompat</item>
        <item name="android:windowBackground">@drawable/abc_dialog_material_background_dark</item>
        <item name="android:windowIsFloating">true</item>
        <item name="android:backgroundDimEnabled">true</item>
        <item name="android:windowContentOverlay">@null</item>
        <item name="android:windowAnimationStyle">@style/Animation.AppCompat.Dialog</item>
        <item name="android:windowSoftInputMode">stateUnspecified|adjustPan</item>

        <item name="windowActionBar">false</item>
        <item name="windowActionModeOverlay">true</item>

        <item name="listPreferredItemPaddingLeft">24dip</item>
        <item name="listPreferredItemPaddingRight">24dip</item>

        <item name="android:listDivider">@null</item>
    </style>
    <style name="Base.V7.Theme.AppCompat.Light" parent="Platform.AppCompat.Light">
        <item name="windowNoTitle">false</item>
        <item name="windowActionBar">true</item>
        <item name="windowActionBarOverlay">false</item>
        <item name="windowActionModeOverlay">false</item>
        <item name="actionBarPopupTheme">@null</item>

        <!-- Used by MediaRouter -->
        <item name="isLightTheme">true</item>

        <item name="selectableItemBackground">@drawable/abc_item_background_holo_light</item>
        <item name="selectableItemBackgroundBorderless">?attr/selectableItemBackground</item>
        <item name="borderlessButtonStyle">@style/Widget.AppCompat.Button.Borderless</item>
        <item name="homeAsUpIndicator">@drawable/abc_ic_ab_back_mtrl_am_alpha</item>

        <item name="dividerVertical">@drawable/abc_list_divider_mtrl_alpha</item>
        <item name="dividerHorizontal">@drawable/abc_list_divider_mtrl_alpha</item>

        <!-- Action Bar Styles -->
        <item name="actionBarTabStyle">@style/Widget.AppCompat.Light.ActionBar.TabView</item>
        <item name="actionBarTabBarStyle">@style/Widget.AppCompat.Light.ActionBar.TabBar</item>
        <item name="actionBarTabTextStyle">@style/Widget.AppCompat.Light.ActionBar.TabText</item>
        <item name="actionButtonStyle">@style/Widget.AppCompat.Light.ActionButton</item>
        <item name="actionOverflowButtonStyle">@style/Widget.AppCompat.Light.ActionButton.Overflow</item>
        <item name="actionOverflowMenuStyle">@style/Widget.AppCompat.Light.PopupMenu.Overflow</item>
        <item name="actionBarStyle">@style/Widget.AppCompat.Light.ActionBar.Solid</item>
        <item name="actionBarSplitStyle">?attr/actionBarStyle</item>
        <item name="actionBarWidgetTheme">@null</item>
        <item name="actionBarTheme">@style/ThemeOverlay.AppCompat.ActionBar</item>
        <item name="actionBarSize">@dimen/abc_action_bar_default_height_material</item>
        <item name="actionBarDivider">?attr/dividerVertical</item>
        <item name="actionBarItemBackground">?attr/selectableItemBackgroundBorderless</item>
        <item name="actionMenuTextAppearance">@style/TextAppearance.AppCompat.Widget.ActionBar.Menu</item>
        <item name="actionMenuTextColor">?android:attr/textColorPrimaryDisableOnly</item>

        <!-- Action Mode -->
        <item name="actionModeStyle">@style/Widget.AppCompat.ActionMode</item>
        <item name="actionModeBackground">@drawable/abc_cab_background_top_material</item>
        <item name="actionModeSplitBackground">?attr/colorPrimaryDark</item>
        <item name="actionModeCloseDrawable">@drawable/abc_ic_ab_back_mtrl_am_alpha</item>
        <item name="actionModeCloseButtonStyle">@style/Widget.AppCompat.ActionButton.CloseMode</item>

        <item name="actionModeCutDrawable">@drawable/abc_ic_menu_cut_mtrl_alpha</item>
        <item name="actionModeCopyDrawable">@drawable/abc_ic_menu_copy_mtrl_am_alpha</item>
        <item name="actionModePasteDrawable">@drawable/abc_ic_menu_paste_mtrl_am_alpha</item>
        <item name="actionModeSelectAllDrawable">@drawable/abc_ic_menu_selectall_mtrl_alpha</item>
        <item name="actionModeShareDrawable">@drawable/abc_ic_menu_share_mtrl_alpha</item>

        <!-- Dropdown Spinner Attributes -->
        <item name="actionDropDownStyle">@style/Widget.AppCompat.Light.Spinner.DropDown.ActionBar</item>

        <!-- Panel attributes -->
        <item name="panelMenuListWidth">@dimen/abc_panel_menu_list_width</item>
        <item name="panelMenuListTheme">@style/Theme.AppCompat.CompactMenu</item>
        <item name="panelBackground">@drawable/abc_menu_hardkey_panel_mtrl_mult</item>
        <item name="android:panelBackground">@android:color/transparent</item>
        <item name="listChoiceBackgroundIndicator">@drawable/abc_list_selector_holo_light</item>

        <!-- List attributes -->
        <item name="textAppearanceListItem">@style/TextAppearance.AppCompat.Subhead</item>
        <item name="textAppearanceListItemSmall">@style/TextAppearance.AppCompat.Subhead</item>
        <item name="listPreferredItemHeight">64dp</item>
        <item name="listPreferredItemHeightSmall">48dp</item>
        <item name="listPreferredItemHeightLarge">80dp</item>
        <item name="listPreferredItemPaddingLeft">@dimen/abc_list_item_padding_horizontal_material</item>
        <item name="listPreferredItemPaddingRight">@dimen/abc_list_item_padding_horizontal_material</item>

        <!-- Spinner styles -->
        <item name="spinnerStyle">@style/Widget.AppCompat.Spinner</item>
        <item name="android:spinnerItemStyle">@style/Widget.AppCompat.TextView.SpinnerItem</item>
        <item name="android:dropDownListViewStyle">@style/Widget.AppCompat.ListView.DropDown</item>

        <!-- Required for use of support_simple_spinner_dropdown_item.xml -->
        <item name="spinnerDropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
        <item name="dropdownListPreferredItemHeight">?attr/listPreferredItemHeightSmall</item>

        <!-- Popup Menu styles -->
        <item name="popupMenuStyle">@style/Widget.AppCompat.Light.PopupMenu</item>
        <item name="textAppearanceLargePopupMenu">@style/TextAppearance.AppCompat.Light.Widget.PopupMenu.Large</item>
        <item name="textAppearanceSmallPopupMenu">@style/TextAppearance.AppCompat.Light.Widget.PopupMenu.Small</item>
        <item name="listPopupWindowStyle">@style/Widget.AppCompat.ListPopupWindow</item>
        <item name="dropDownListViewStyle">?android:attr/dropDownListViewStyle</item>

        <!-- SearchView attributes -->
        <item name="searchViewStyle">@style/Widget.AppCompat.Light.SearchView</item>
        <item name="android:dropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
        <item name="textColorSearchUrl">@color/abc_search_url_text</item>
        <item name="textAppearanceSearchResultTitle">@style/TextAppearance.AppCompat.SearchResult.Title</item>
        <item name="textAppearanceSearchResultSubtitle">@style/TextAppearance.AppCompat.SearchResult.Subtitle</item>

        <!-- ShareActionProvider attributes -->
        <item name="activityChooserViewStyle">@style/Widget.AppCompat.ActivityChooserView</item>

        <!-- Toolbar styles -->
        <item name="toolbarStyle">@style/Widget.AppCompat.Toolbar</item>
        <item name="toolbarNavigationButtonStyle">@style/Widget.AppCompat.Toolbar.Button.Navigation</item>

        <item name="editTextStyle">@style/Widget.AppCompat.EditText</item>
        <item name="editTextBackground">@drawable/abc_edit_text_material</item>
        <item name="editTextColor">?android:attr/textColorPrimary</item>
        <item name="autoCompleteTextViewStyle">@style/Widget.AppCompat.AutoCompleteTextView</item>

        <!-- Color palette -->
        <item name="colorPrimaryDark">@color/primary_dark_material_light</item>
        <item name="colorPrimary">@color/primary_material_light</item>
        <item name="colorAccent">@color/accent_material_light</item>

        <item name="colorControlNormal">?android:attr/textColorSecondary</item>
        <item name="colorControlActivated">?attr/colorAccent</item>
        <item name="colorControlHighlight">@color/ripple_material_light</item>
        <item name="colorButtonNormal">@color/button_material_light</item>
        <item name="colorSwitchThumbNormal">@color/switch_thumb_material_light</item>
        <item name="controlBackground">?attr/selectableItemBackgroundBorderless</item>

        <item name="drawerArrowStyle">@style/Widget.AppCompat.DrawerArrowToggle</item>

        <item name="checkboxStyle">@style/Widget.AppCompat.CompoundButton.CheckBox</item>
        <item name="radioButtonStyle">@style/Widget.AppCompat.CompoundButton.RadioButton</item>
        <item name="switchStyle">@style/Widget.AppCompat.CompoundButton.Switch</item>

        <item name="ratingBarStyle">@style/Widget.AppCompat.RatingBar</item>
        <item name="ratingBarStyleIndicator">@style/Widget.AppCompat.RatingBar.Indicator</item>
        <item name="ratingBarStyleSmall">@style/Widget.AppCompat.RatingBar.Small</item>
        <item name="seekBarStyle">@style/Widget.AppCompat.SeekBar</item>

        <!-- Button styles -->
        <item name="buttonStyle">@style/Widget.AppCompat.Button</item>
        <item name="buttonStyleSmall">@style/Widget.AppCompat.Button.Small</item>
        <item name="android:textAppearanceButton">@style/TextAppearance.AppCompat.Widget.Button</item>

        <item name="imageButtonStyle">@style/Widget.AppCompat.ImageButton</item>

        <item name="buttonBarStyle">@style/Widget.AppCompat.ButtonBar</item>
        <item name="buttonBarButtonStyle">@style/Widget.AppCompat.Button.ButtonBar.AlertDialog</item>
        <item name="buttonBarPositiveButtonStyle">?attr/buttonBarButtonStyle</item>
        <item name="buttonBarNegativeButtonStyle">?attr/buttonBarButtonStyle</item>
        <item name="buttonBarNeutralButtonStyle">?attr/buttonBarButtonStyle</item>

        <!-- Dialog attributes -->
        <item name="dialogTheme">@style/Theme.AppCompat.Light.Dialog</item>
        <item name="dialogPreferredPadding">@dimen/abc_dialog_padding_material</item>

        <item name="alertDialogTheme">@style/Theme.AppCompat.Light.Dialog.Alert</item>
        <item name="alertDialogStyle">@style/AlertDialog.AppCompat.Light</item>
        <item name="alertDialogCenterButtons">false</item>
        <item name="textColorAlertDialogListItem">@color/abc_primary_text_material_light</item>
        <item name="listDividerAlertDialog">@null</item>

        <!-- Define these here; ContextThemeWrappers around themes that define them should
             always clear these values. -->
        <item name="windowFixedWidthMajor">0dp</item>
        <item name="windowFixedWidthMinor">0dp</item>
        <item name="windowFixedHeightMajor">0dp</item>
        <item name="windowFixedHeightMinor">0dp</item>
    </style>
    <style name="Base.V7.Theme.AppCompat.Light.Dialog" parent="Base.Theme.AppCompat.Light">
        <item name="android:colorBackground">@color/background_floating_material_light</item>
        <item name="android:colorBackgroundCacheHint">@null</item>

        <item name="android:windowFrame">@null</item>
        <item name="android:windowTitleStyle">@style/RtlOverlay.DialogWindowTitle.AppCompat</item>
        <item name="android:windowTitleBackgroundStyle">@style/Base.DialogWindowTitleBackground.AppCompat</item>
        <item name="android:windowBackground">@drawable/abc_dialog_material_background_light</item>
        <item name="android:windowIsFloating">true</item>
        <item name="android:backgroundDimEnabled">true</item>
        <item name="android:windowContentOverlay">@null</item>
        <item name="android:windowAnimationStyle">@style/Animation.AppCompat.Dialog</item>
        <item name="android:windowSoftInputMode">stateUnspecified|adjustPan</item>

        <item name="windowActionBar">false</item>
        <item name="windowActionModeOverlay">true</item>

        <item name="listPreferredItemPaddingLeft">24dip</item>
        <item name="listPreferredItemPaddingRight">24dip</item>

        <item name="android:listDivider">@null</item>
    </style>
    <style name="Base.V7.Widget.AppCompat.AutoCompleteTextView" parent="android:Widget.AutoCompleteTextView">
        <item name="android:dropDownSelector">?attr/listChoiceBackgroundIndicator</item>
        <item name="android:popupBackground">@drawable/abc_popup_background_mtrl_mult</item>
        <item name="android:background">?attr/editTextBackground</item>
        <item name="android:textColor">?attr/editTextColor</item>
        <item name="android:textAppearance">?android:attr/textAppearanceMediumInverse</item>
    </style>
    <style name="Base.V7.Widget.AppCompat.EditText" parent="android:Widget.EditText">
        <item name="android:background">?attr/editTextBackground</item>
        <item name="android:textColor">?attr/editTextColor</item>
        <item name="android:textAppearance">?android:attr/textAppearanceMediumInverse</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionBar" parent="">
        <item name="displayOptions">showTitle</item>
        <item name="divider">?attr/dividerVertical</item>
        <item name="height">?attr/actionBarSize</item>

        <item name="titleTextStyle">@style/TextAppearance.AppCompat.Widget.ActionBar.Title</item>
        <item name="subtitleTextStyle">@style/TextAppearance.AppCompat.Widget.ActionBar.Subtitle</item>

        <item name="background">@null</item>
        <item name="backgroundStacked">@null</item>
        <item name="backgroundSplit">@null</item>

        <item name="actionButtonStyle">@style/Widget.AppCompat.ActionButton</item>
        <item name="actionOverflowButtonStyle">@style/Widget.AppCompat.ActionButton.Overflow</item>

        <item name="android:gravity">center_vertical</item>
        <item name="contentInsetStart">@dimen/abc_action_bar_content_inset_material</item>
        <item name="contentInsetEnd">@dimen/abc_action_bar_content_inset_material</item>
        <item name="elevation">8dp</item>
        <item name="popupTheme">?attr/actionBarPopupTheme</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionBar.Solid">
        <item name="background">?attr/colorPrimary</item>
        <item name="backgroundStacked">?attr/colorPrimary</item>
        <item name="backgroundSplit">?attr/colorPrimary</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionBar.TabBar" parent="">
        <item name="divider">?attr/actionBarDivider</item>
        <item name="showDividers">middle</item>
        <item name="dividerPadding">8dip</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionBar.TabText" parent="">
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Medium</item>
        <item name="android:textColor">?android:attr/textColorPrimary</item>
        <item name="android:textSize">12sp</item>
        <item name="android:textStyle">bold</item>
        <item name="android:ellipsize">marquee</item>
        <item name="android:maxLines">2</item>
        <item name="android:maxWidth">180dp</item>
        <item name="textAllCaps">true</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionBar.TabView" parent="">
        <item name="android:background">@drawable/abc_tab_indicator_material</item>
        <item name="android:gravity">center_horizontal</item>
        <item name="android:paddingLeft">16dip</item>
        <item name="android:paddingRight">16dip</item>
        <item name="android:layout_width">0dip</item>
        <item name="android:layout_weight">1</item>
        <item name="android:minWidth">80dip</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionButton" parent="RtlUnderlay.Widget.AppCompat.ActionButton">
        <item name="android:background">?attr/actionBarItemBackground</item>
        <item name="android:minWidth">@dimen/abc_action_button_min_width_material</item>
        <item name="android:minHeight">@dimen/abc_action_button_min_height_material</item>
        <item name="android:scaleType">center</item>
        <item name="android:gravity">center</item>
        <item name="android:maxLines">2</item>
        <item name="textAllCaps">@bool/abc_config_actionMenuItemAllCaps</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionButton.CloseMode">
        <item name="android:background">?attr/controlBackground</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionButton.Overflow" parent="RtlUnderlay.Widget.AppCompat.ActionButton.Overflow">
        <item name="android:src">@drawable/abc_ic_menu_moreoverflow_mtrl_alpha</item>
        <item name="android:background">?attr/actionBarItemBackground</item>
        <item name="android:contentDescription">@string/abc_action_menu_overflow_description</item>
        <item name="android:minWidth">@dimen/abc_action_button_min_width_overflow_material</item>
        <item name="android:minHeight">@dimen/abc_action_button_min_height_material</item>
    </style>
    <style name="Base.Widget.AppCompat.ActionMode" parent="">
        <item name="background">?attr/actionModeBackground</item>
        <item name="backgroundSplit">?attr/actionModeSplitBackground</item>
        <item name="height">?attr/actionBarSize</item>
        <item name="titleTextStyle">@style/TextAppearance.AppCompat.Widget.ActionMode.Title</item>
        <item name="subtitleTextStyle">@style/TextAppearance.AppCompat.Widget.ActionMode.Subtitle</item>
        <item name="closeItemLayout">@layout/abc_action_mode_close_item_material</item>
    </style>
    <style name="Base.Widget.AppCompat.ActivityChooserView" parent="">
        <item name="android:gravity">center</item>
        <item name="android:background">@drawable/abc_ab_share_pack_mtrl_alpha</item>
        <item name="divider">?attr/dividerVertical</item>
        <item name="showDividers">middle</item>
        <item name="dividerPadding">6dip</item>
    </style>
    <style name="Base.Widget.AppCompat.AutoCompleteTextView" parent="Base.V7.Widget.AppCompat.AutoCompleteTextView"/>
    <style name="Base.Widget.AppCompat.Button" parent="android:Widget">
        <item name="android:background">@drawable/abc_btn_default_mtrl_shape</item>
        <item name="android:textAppearance">?android:attr/textAppearanceButton</item>
        <item name="android:minHeight">48dip</item>
        <item name="android:minWidth">88dip</item>
        <item name="android:focusable">true</item>
        <item name="android:clickable">true</item>
        <item name="android:gravity">center_vertical|center_horizontal</item>
    </style>
    <style name="Base.Widget.AppCompat.Button.Borderless">
        <item name="android:background">@drawable/abc_btn_borderless_material</item>
    </style>
    <style name="Base.Widget.AppCompat.Button.Borderless.Colored">
        <item name="android:textColor">?attr/colorAccent</item>
    </style>
    <style name="Base.Widget.AppCompat.Button.ButtonBar.AlertDialog" parent="Widget.AppCompat.Button.Borderless.Colored">
        <item name="android:minWidth">64dp</item>
        <item name="android:maxLines">2</item>
        <item name="android:minHeight">@dimen/abc_alert_dialog_button_bar_height</item>
    </style>
    <style name="Base.Widget.AppCompat.Button.Colored">
        <item name="android:background">@drawable/abc_btn_colored_material</item>
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Widget.Button.Inverse</item>
    </style>
    <style name="Base.Widget.AppCompat.Button.Small">
        <item name="android:minHeight">48dip</item>
        <item name="android:minWidth">48dip</item>
    </style>
    <style name="Base.Widget.AppCompat.ButtonBar" parent="android:Widget">
        <item name="android:background">@null</item>
    </style>
    <style name="Base.Widget.AppCompat.ButtonBar.AlertDialog"/>
    <style name="Base.Widget.AppCompat.CompoundButton.CheckBox" parent="android:Widget.CompoundButton.CheckBox">
        <item name="android:button">?android:attr/listChoiceIndicatorMultiple</item>
        <item name="android:background">?attr/controlBackground</item>
    </style>
    <style name="Base.Widget.AppCompat.CompoundButton.RadioButton" parent="android:Widget.CompoundButton.RadioButton">
        <item name="android:button">?android:attr/listChoiceIndicatorSingle</item>
        <item name="android:background">?attr/controlBackground</item>
    </style>
    <style name="Base.Widget.AppCompat.CompoundButton.Switch" parent="android:Widget.CompoundButton">
        <item name="track">@drawable/abc_switch_track_mtrl_alpha</item>
        <item name="android:thumb">@drawable/abc_switch_thumb_material</item>
        <item name="switchTextAppearance">@style/TextAppearance.AppCompat.Widget.Switch</item>
        <item name="android:background">?attr/controlBackground</item>
        <item name="showText">false</item>
        <item name="switchPadding">@dimen/abc_switch_padding</item>
        <item name="android:textOn">@string/abc_capital_on</item>
        <item name="android:textOff">@string/abc_capital_off</item>
    </style>
    <style name="Base.Widget.AppCompat.DrawerArrowToggle" parent="Base.Widget.AppCompat.DrawerArrowToggle.Common">
        <item name="barLength">18dp</item>
        <item name="gapBetweenBars">3dp</item>
        <item name="drawableSize">24dp</item>
    </style>
    <style name="Base.Widget.AppCompat.DrawerArrowToggle.Common" parent="">
        <item name="color">?android:attr/textColorSecondary</item>
        <item name="spinBars">true</item>
        <item name="thickness">2dp</item>
        <item name="arrowShaftLength">16dp</item>
        <item name="arrowHeadLength">8dp</item>
    </style>
    <style name="Base.Widget.AppCompat.DropDownItem.Spinner" parent="">
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Widget.DropDownItem</item>
        <item name="android:paddingLeft">8dp</item>
        <item name="android:paddingRight">8dp</item>
        <item name="android:gravity">center_vertical</item>
    </style>
    <style name="Base.Widget.AppCompat.EditText" parent="Base.V7.Widget.AppCompat.EditText"/>
    <style name="Base.Widget.AppCompat.ImageButton" parent="android:Widget.ImageButton">
        <item name="android:background">@drawable/abc_btn_default_mtrl_shape</item>
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar" parent="Base.Widget.AppCompat.ActionBar">
        <item name="actionButtonStyle">@style/Widget.AppCompat.Light.ActionButton</item>
        <item name="actionOverflowButtonStyle">@style/Widget.AppCompat.Light.ActionButton.Overflow</item>
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar.Solid">
        <item name="background">?attr/colorPrimary</item>
        <item name="backgroundStacked">?attr/colorPrimary</item>
        <item name="backgroundSplit">?attr/colorPrimary</item>
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar.TabBar" parent="Base.Widget.AppCompat.ActionBar.TabBar">
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar.TabText" parent="Base.Widget.AppCompat.ActionBar.TabText">
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar.TabText.Inverse" parent="Base.Widget.AppCompat.Light.ActionBar.TabText">
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Medium.Inverse</item>
    </style>
    <style name="Base.Widget.AppCompat.Light.ActionBar.TabView" parent="Base.Widget.AppCompat.ActionBar.TabView">
        <item name="android:background">@drawable/abc_tab_indicator_material</item>
    </style>
    <style name="Base.Widget.AppCompat.Light.PopupMenu" parent="@style/Widget.AppCompat.ListPopupWindow">
    </style>
    <style name="Base.Widget.AppCompat.Light.PopupMenu.Overflow">
        <item name="overlapAnchor">true</item>
        <item name="android:dropDownHorizontalOffset">-4dip</item>
    </style>
    <style name="Base.Widget.AppCompat.ListPopupWindow" parent="">
        <item name="android:dropDownSelector">?attr/listChoiceBackgroundIndicator</item>
        <item name="android:popupBackground">@drawable/abc_popup_background_mtrl_mult</item>
        <item name="android:dropDownVerticalOffset">0dip</item>
        <item name="android:dropDownHorizontalOffset">0dip</item>
        <item name="android:dropDownWidth">wrap_content</item>
    </style>
    <style name="Base.Widget.AppCompat.ListView" parent="android:Widget.ListView">
        <item name="android:listSelector">?attr/listChoiceBackgroundIndicator</item>
    </style>
    <style name="Base.Widget.AppCompat.ListView.DropDown">
        <item name="android:divider">@null</item>
    </style>
    <style name="Base.Widget.AppCompat.ListView.Menu" parent="android:Widget.ListView.Menu">
        <item name="android:listSelector">?attr/listChoiceBackgroundIndicator</item>
        <item name="android:divider">?attr/dividerHorizontal</item>
    </style>
    <style name="Base.Widget.AppCompat.PopupMenu" parent="@style/Widget.AppCompat.ListPopupWindow">
    </style>
    <style name="Base.Widget.AppCompat.PopupMenu.Overflow">
        <item name="overlapAnchor">true</item>
        <item name="android:dropDownHorizontalOffset">-4dip</item>
    </style>
    <style name="Base.Widget.AppCompat.PopupWindow" parent="android:Widget.PopupWindow">
    </style>
    <style name="Base.Widget.AppCompat.ProgressBar" parent="android:Widget.ProgressBar">
        <item name="android:minWidth">@dimen/abc_action_bar_progress_bar_size</item>
        <item name="android:maxWidth">@dimen/abc_action_bar_progress_bar_size</item>
        <item name="android:minHeight">@dimen/abc_action_bar_progress_bar_size</item>
        <item name="android:maxHeight">@dimen/abc_action_bar_progress_bar_size</item>
    </style>
    <style name="Base.Widget.AppCompat.ProgressBar.Horizontal" parent="android:Widget.ProgressBar.Horizontal">
    </style>
    <style name="Base.Widget.AppCompat.RatingBar" parent="android:Widget.RatingBar">
        <item name="android:progressDrawable">@drawable/abc_ratingbar_full_material</item>
        <item name="android:indeterminateDrawable">@drawable/abc_ratingbar_full_material</item>
    </style>
    <style name="Base.Widget.AppCompat.RatingBar.Indicator" parent="android:Widget.RatingBar">
        <item name="android:progressDrawable">@drawable/abc_ratingbar_indicator_material</item>
        <item name="android:indeterminateDrawable">@drawable/abc_ratingbar_indicator_material</item>
        <item name="android:minHeight">36dp</item>
        <item name="android:maxHeight">36dp</item>
        <item name="android:isIndicator">true</item>
        <item name="android:thumb">@null</item>
    </style>
    <style name="Base.Widget.AppCompat.RatingBar.Small" parent="android:Widget.RatingBar">
        <item name="android:progressDrawable">@drawable/abc_ratingbar_small_material</item>
        <item name="android:indeterminateDrawable">@drawable/abc_ratingbar_small_material</item>
        <item name="android:minHeight">16dp</item>
        <item name="android:maxHeight">16dp</item>
        <item name="android:isIndicator">true</item>
        <item name="android:thumb">@null</item>
    </style>
    <style name="Base.Widget.AppCompat.SearchView" parent="android:Widget">
        <item name="layout">@layout/abc_search_view</item>
        <item name="queryBackground">@drawable/abc_textfield_search_material</item>
        <item name="submitBackground">@drawable/abc_textfield_search_material</item>
        <item name="closeIcon">@drawable/abc_ic_clear_mtrl_alpha</item>
        <item name="searchIcon">@drawable/abc_ic_search_api_mtrl_alpha</item>
        <item name="searchHintIcon">@drawable/abc_ic_search_api_mtrl_alpha</item>
        <item name="goIcon">@drawable/abc_ic_go_search_api_mtrl_alpha</item>
        <item name="voiceIcon">@drawable/abc_ic_voice_search_api_mtrl_alpha</item>
        <item name="commitIcon">@drawable/abc_ic_commit_search_api_mtrl_alpha</item>
        <item name="suggestionRowLayout">@layout/abc_search_dropdown_item_icons_2line</item>
    </style>
    <style name="Base.Widget.AppCompat.SearchView.ActionBar">
        <item name="queryBackground">@null</item>
        <item name="submitBackground">@null</item>
        <item name="searchHintIcon">@null</item>
        <item name="defaultQueryHint">@string/abc_search_hint</item>
    </style>
    <style name="Base.Widget.AppCompat.SeekBar" parent="android:Widget">
        <item name="android:indeterminateOnly">false</item>
        <item name="android:progressDrawable">@drawable/abc_seekbar_track_material</item>
        <item name="android:indeterminateDrawable">@drawable/abc_seekbar_track_material</item>
        <item name="android:thumb">@drawable/abc_seekbar_thumb_material</item>
        <item name="android:focusable">true</item>
        <item name="android:paddingLeft">16dip</item>
        <item name="android:paddingRight">16dip</item>
    </style>
    <style name="Base.Widget.AppCompat.Spinner" parent="Platform.Widget.AppCompat.Spinner">
        <item name="android:background">@drawable/abc_spinner_mtrl_am_alpha</item>
        <item name="android:popupBackground">@drawable/abc_popup_background_mtrl_mult</item>
        <item name="android:dropDownSelector">?attr/listChoiceBackgroundIndicator</item>
        <item name="android:dropDownVerticalOffset">0dip</item>
        <item name="android:dropDownHorizontalOffset">0dip</item>
        <item name="android:dropDownWidth">wrap_content</item>
        <item name="android:clickable">true</item>
        <item name="android:gravity">left|start|center_vertical</item>
        <item name="overlapAnchor">true</item>
    </style>
    <style name="Base.Widget.AppCompat.Spinner.Underlined">
        <item name="android:background">@drawable/abc_spinner_textfield_background_material</item>
    </style>
    <style name="Base.Widget.AppCompat.TextView.SpinnerItem" parent="android:Widget.TextView.SpinnerItem">
        <item name="android:textAppearance">@style/TextAppearance.AppCompat.Widget.TextView.SpinnerItem</item>
        <item name="android:paddingLeft">8dp</item>
        <item name="android:paddingRight">8dp</item>
    </style>
    <style name="Base.Widget.AppCompat.Toolbar" parent="android:Widget">
        <item name="titleTextAppearance">@style/TextAppearance.Widget.AppCompat.Toolbar.Title</item>
        <item name="subtitleTextAppearance">@style/TextAppearance.Widget.AppCompat.Toolbar.Subtitle</item>
        <item name="android:minHeight">?attr/actionBarSize</item>
        <item name="titleMargins">4dp</item>
        <item name="maxButtonHeight">@dimen/abc_action_bar_default_height_material</item>
        <item name="collapseIcon">?attr/homeAsUpIndicator</item>
        <item name="collapseContentDescription">@string/abc_toolbar_collapse_description</item>
        <item name="contentInsetStart">16dp</item>
        <item name="android:paddingLeft">@dimen/abc_action_bar_default_padding_start_material</item>
        <item name="android:paddingRight">@dimen/abc_action_bar_default_padding_end_material</item>
    </style>
    <style name="Base.Widget.AppCompat.Toolbar.Button.Navigation" parent="android:Widget">
        <item name="android:background">?attr/controlBackground</item>
        <item name="android:minWidth">56dp</item>
        <item name="android:scaleType">center</item>
    </style>
    <style name="Platform.AppCompat" parent="android:Theme">
        <item name="android:windowNoTitle">true</item>

        <!-- Window colors -->
        <item name="android:colorForeground">@color/foreground_material_dark</item>
        <item name="android:colorForegroundInverse">@color/foreground_material_light</item>
        <item name="android:colorBackground">@color/background_material_dark</item>
        <item name="android:colorBackgroundCacheHint">@color/abc_background_cache_hint_selector_material_dark</item>
        <item name="android:disabledAlpha">@dimen/abc_disabled_alpha_material_dark</item>
        <item name="android:backgroundDimAmount">0.6</item>
        <item name="android:windowBackground">@color/background_material_dark</item>

        <!-- Text colors -->
        <item name="android:textColorPrimary">@color/abc_primary_text_material_dark</item>
        <item name="android:textColorPrimaryInverse">@color/abc_primary_text_material_light</item>
        <item name="android:textColorPrimaryDisableOnly">@color/abc_primary_text_disable_only_material_dark</item>
        <item name="android:textColorSecondary">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorSecondaryInverse">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorTertiary">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorTertiaryInverse">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorHint">@color/hint_foreground_material_dark</item>
        <item name="android:textColorHintInverse">@color/hint_foreground_material_light</item>
        <item name="android:textColorHighlight">@color/highlighted_text_material_dark</item>
        <item name="android:textColorLink">?attr/colorAccent</item>

        <!-- Text styles -->
        <item name="android:textAppearance">@style/TextAppearance.AppCompat</item>
        <item name="android:textAppearanceInverse">@style/TextAppearance.AppCompat.Inverse</item>
        <item name="android:textAppearanceLarge">@style/TextAppearance.AppCompat.Large</item>
        <item name="android:textAppearanceLargeInverse">@style/TextAppearance.AppCompat.Large.Inverse</item>
        <item name="android:textAppearanceMedium">@style/TextAppearance.AppCompat.Medium</item>
        <item name="android:textAppearanceMediumInverse">@style/TextAppearance.AppCompat.Medium.Inverse</item>
        <item name="android:textAppearanceSmall">@style/TextAppearance.AppCompat.Small</item>
        <item name="android:textAppearanceSmallInverse">@style/TextAppearance.AppCompat.Small.Inverse</item>

        <item name="android:listChoiceIndicatorSingle">@drawable/abc_btn_radio_material</item>
        <item name="android:listChoiceIndicatorMultiple">@drawable/abc_btn_check_material</item>
    </style>
    <style name="Platform.AppCompat.Light" parent="android:Theme.Light">
        <item name="android:windowNoTitle">true</item>

        <!-- Window colors -->
        <item name="android:colorForeground">@color/foreground_material_light</item>
        <item name="android:colorForegroundInverse">@color/foreground_material_dark</item>
        <item name="android:colorBackground">@color/background_material_light</item>
        <item name="android:colorBackgroundCacheHint">@color/abc_background_cache_hint_selector_material_light</item>
        <item name="android:disabledAlpha">@dimen/abc_disabled_alpha_material_light</item>
        <item name="android:backgroundDimAmount">0.6</item>
        <item name="android:windowBackground">@color/background_material_light</item>

        <!-- Text colors -->
        <item name="android:textColorPrimary">@color/abc_primary_text_material_light</item>
        <item name="android:textColorPrimaryInverse">@color/abc_primary_text_material_dark</item>
        <item name="android:textColorSecondary">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorSecondaryInverse">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorTertiary">@color/abc_secondary_text_material_light</item>
        <item name="android:textColorTertiaryInverse">@color/abc_secondary_text_material_dark</item>
        <item name="android:textColorPrimaryDisableOnly">@color/abc_primary_text_disable_only_material_light</item>
        <item name="android:textColorPrimaryInverseDisableOnly">@color/abc_primary_text_disable_only_material_dark</item>
        <item name="android:textColorHint">@color/hint_foreground_material_light</item>
        <item name="android:textColorHintInverse">@color/hint_foreground_material_dark</item>
        <item name="android:textColorHighlight">@color/highlighted_text_material_light</item>
        <item name="android:textColorLink">?attr/colorAccent</item>

        <!-- Text styles -->
        <item name="android:textAppearance">@style/TextAppearance.AppCompat</item>
        <item name="android:textAppearanceInverse">@style/TextAppearance.AppCompat.Inverse</item>
        <item name="android:textAppearanceLarge">@style/TextAppearance.AppCompat.Large</item>
        <item name="android:textAppearanceLargeInverse">@style/TextAppearance.AppCompat.Large.Inverse</item>
        <item name="android:textAppearanceMedium">@style/TextAppearance.AppCompat.Medium</item>
        <item name="android:textAppearanceMediumInverse">@style/TextAppearance.AppCompat.Medium.Inverse</item>
        <item name="android:textAppearanceSmall">@style/TextAppearance.AppCompat.Small</item>
        <item name="android:textAppearanceSmallInverse">@style/TextAppearance.AppCompat.Small.Inverse</item>

        <item name="android:listChoiceIndicatorSingle">@drawable/abc_btn_radio_material</item>
        <item name="android:listChoiceIndicatorMultiple">@drawable/abc_btn_check_material</item>
    </style>
    <style name="Platform.ThemeOverlay.AppCompat" parent=""/>
    <style name="Platform.ThemeOverlay.AppCompat.Dark">
        <!-- Action Bar styles -->
        <item name="actionBarItemBackground">@drawable/abc_item_background_holo_dark</item>
        <item name="actionDropDownStyle">@style/Widget.AppCompat.Spinner.DropDown.ActionBar</item>
        <item name="selectableItemBackground">@drawable/abc_item_background_holo_dark</item>

        <!-- SearchView styles -->
        <item name="android:autoCompleteTextViewStyle">@style/Widget.AppCompat.AutoCompleteTextView</item>
        <item name="android:dropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
    </style>
    <style name="Platform.ThemeOverlay.AppCompat.Light">
        <item name="actionBarItemBackground">@drawable/abc_item_background_holo_light</item>
        <item name="actionDropDownStyle">@style/Widget.AppCompat.Light.Spinner.DropDown.ActionBar</item>
        <item name="selectableItemBackground">@drawable/abc_item_background_holo_light</item>

        <!-- SearchView attributes -->
        <item name="android:autoCompleteTextViewStyle">@style/Widget.AppCompat.Light.AutoCompleteTextView</item>
        <item name="android:dropDownItemStyle">@style/Widget.AppCompat.DropDownItem.Spinner</item>
    </style>
    <style name="Platform.Widget.AppCompat.Spinner" parent="android:Widget.Spinner"/>
    <style name="RtlOverlay.DialogWindowTitle.AppCompat" parent="Base.DialogWindowTitle.AppCompat">
    </style>
    <style name="RtlOverlay.Widget.AppCompat.ActionBar.TitleItem" parent="android:Widget">
        <item name="android:layout_gravity">center_vertical|left</item>
        <item name="android:paddingRight">8dp</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.DialogTitle.Icon" parent="android:Widget">
        <item name="android:layout_marginRight">8dp</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.PopupMenuItem" parent="android:Widget">
        <item name="android:paddingRight">16dp</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.PopupMenuItem.InternalGroup" parent="android:Widget">
        <item name="android:layout_marginLeft">16dp</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.PopupMenuItem.Text" parent="android:Widget">
        <item name="android:layout_alignParentLeft">true</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.Search.DropDown" parent="android:Widget">
        <item name="android:paddingLeft">@dimen/abc_dropdownitem_text_padding_left</item>
        <item name="android:paddingRight">4dp</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.Search.DropDown.Icon1" parent="android:Widget">
        <item name="android:layout_alignParentLeft">true</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.Search.DropDown.Icon2" parent="android:Widget">
        <item name="android:layout_toLeftOf">@id/edit_query</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.Search.DropDown.Query" parent="android:Widget">
        <item name="android:layout_alignParentRight">true</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.Search.DropDown.Text" parent="Base.Widget.AppCompat.DropDownItem.Spinner">
        <item name="android:layout_toLeftOf">@android:id/icon2</item>
        <item name="android:layout_toRightOf">@android:id/icon1</item>
    </style>
    <style name="RtlOverlay.Widget.AppCompat.SearchView.MagIcon" parent="android:Widget">
        <item name="android:layout_marginLeft">@dimen/abc_dropdownitem_text_padding_left</item>
    </style>
    <style name="RtlUnderlay.Widget.AppCompat.ActionButton" parent="android:Widget">
        <item name="android:paddingLeft">12dp</item>
        <item name="android:paddingRight">12dp</item>
    </style>
    <style name="RtlUnderlay.Widget.AppCompat.ActionButton.Overflow" parent="Base.Widget.AppCompat.ActionButton">
        <item name="android:paddingLeft">@dimen/abc_action_bar_overflow_padding_start_material</item>
        <item name="android:paddingRight">@dimen/abc_action_bar_overflow_padding_end_material</item>
    </style>
    <style name="TextAppearance.AppCompat" parent="Base.TextAppearance.AppCompat"/>
    <style name="TextAppearance.AppCompat.Body1" parent="Base.TextAppearance.AppCompat.Body1"/>
    <style name="TextAppearance.AppCompat.Body2" parent="Base.TextAppearance.AppCompat.Body2"/>
    <style name="TextAppearance.AppCompat.Button" parent="Base.TextAppearance.AppCompat.Button"/>
    <style name="TextAppearance.AppCompat.Caption" parent="Base.TextAppearance.AppCompat.Caption"/>
    <style name="TextAppearance.AppCompat.Display1" parent="Base.TextAppearance.AppCompat.Display1"/>
    <style name="TextAppearance.AppCompat.Display2" parent="Base.TextAppearance.AppCompat.Display2"/>
    <style name="TextAppearance.AppCompat.Display3" parent="Base.TextAppearance.AppCompat.Display3"/>
    <style name="TextAppearance.AppCompat.Display4" parent="Base.TextAppearance.AppCompat.Display4"/>
    <style name="TextAppearance.AppCompat.Headline" parent="Base.TextAppearance.AppCompat.Headline"/>
    <style name="TextAppearance.AppCompat.Inverse" parent="Base.TextAppearance.AppCompat.Inverse"/>
    <style name="TextAppearance.AppCompat.Large" parent="Base.TextAppearance.AppCompat.Large"/>
    <style name="TextAppearance.AppCompat.Large.Inverse" parent="Base.TextAppearance.AppCompat.Large.Inverse"/>
    <style name="TextAppearance.AppCompat.Light.SearchResult.Subtitle" parent="TextAppearance.AppCompat.SearchResult.Subtitle"/>
    <style name="TextAppearance.AppCompat.Light.SearchResult.Title" parent="TextAppearance.AppCompat.SearchResult.Title"/>
    <style name="TextAppearance.AppCompat.Light.Widget.PopupMenu.Large" parent="Base.TextAppearance.AppCompat.Light.Widget.PopupMenu.Large">
    </style>
    <style name="TextAppearance.AppCompat.Light.Widget.PopupMenu.Small" parent="Base.TextAppearance.AppCompat.Light.Widget.PopupMenu.Small">
    </style>
    <style name="TextAppearance.AppCompat.Medium" parent="Base.TextAppearance.AppCompat.Medium"/>
    <style name="TextAppearance.AppCompat.Medium.Inverse" parent="Base.TextAppearance.AppCompat.Medium.Inverse"/>
    <style name="TextAppearance.AppCompat.Menu" parent="Base.TextAppearance.AppCompat.Menu"/>
    <style name="TextAppearance.AppCompat.SearchResult.Subtitle" parent="Base.TextAppearance.AppCompat.SearchResult.Subtitle">
    </style>
    <style name="TextAppearance.AppCompat.SearchResult.Title" parent="Base.TextAppearance.AppCompat.SearchResult.Title">
    </style>
    <style name="TextAppearance.AppCompat.Small" parent="Base.TextAppearance.AppCompat.Small"/>
    <style name="TextAppearance.AppCompat.Small.Inverse" parent="Base.TextAppearance.AppCompat.Small.Inverse"/>
    <style name="TextAppearance.AppCompat.Subhead" parent="Base.TextAppearance.AppCompat.Subhead"/>
    <style name="TextAppearance.AppCompat.Subhead.Inverse" parent="Base.TextAppearance.AppCompat.Subhead.Inverse"/>
    <style name="TextAppearance.AppCompat.Title" parent="Base.TextAppearance.AppCompat.Title"/>
    <style name="TextAppearance.AppCompat.Title.Inverse" parent="Base.TextAppearance.AppCompat.Title.Inverse"/>
    <style name="TextAppearance.AppCompat.Widget.ActionBar.Menu" parent="Base.TextAppearance.AppCompat.Widget.ActionBar.Menu">
    </style>
    <style name="TextAppearance.AppCompat.Widget.ActionBar.Subtitle" parent="Base.TextAppearance.AppCompat.Widget.ActionBar.Subtitle"/>
    <style name="TextAppearance.AppCompat.Widget.ActionBar.Subtitle.Inverse" parent="Base.TextAppearance.AppCompat.Widget.ActionBar.Subtitle.Inverse">
    </style>
    <style name="TextAppearance.AppCompat.Widget.ActionBar.Title" parent="Base.TextAppearance.AppCompat.Widget.ActionBar.Title"/>
    <style name="TextAppearance.AppCompat.Widget.ActionBar.Title.Inverse" parent="Base.TextAppearance.AppCompat.Widget.ActionBar.Title.Inverse">
    </style>
    <style name="TextAppearance.AppCompat.Widget.ActionMode.Subtitle" parent="Base.TextAppearance.AppCompat.Widget.ActionMode.Subtitle">
    </style>
    <style name="TextAppearance.AppCompat.Widget.ActionMode.Subtitle.Inverse" parent="TextAppearance.AppCompat.Widget.ActionMode.Subtitle"/>
    <style name="TextAppearance.AppCompat.Widget.ActionMode.Title" parent="Base.TextAppearance.AppCompat.Widget.ActionMode.Title">
    </style>
    <style name="TextAppearance.AppCompat.Widget.ActionMode.Title.Inverse" parent="TextAppearance.AppCompat.Widget.ActionMode.Title"/>
    <style name="TextAppearance.AppCompat.Widget.Button" parent="Base.TextAppearance.AppCompat.Widget.Button"/>
    <style name="TextAppearance.AppCompat.Widget.Button.Inverse" parent="Base.TextAppearance.AppCompat.Widget.Button.Inverse"/>
    <style name="TextAppearance.AppCompat.Widget.DropDownItem" parent="Base.TextAppearance.AppCompat.Widget.DropDownItem">
    </style>
    <style name="TextAppearance.AppCompat.Widget.PopupMenu.Large" parent="Base.TextAppearance.AppCompat.Widget.PopupMenu.Large">
    </style>
    <style name="TextAppearance.AppCompat.Widget.PopupMenu.Small" parent="Base.TextAppearance.AppCompat.Widget.PopupMenu.Small">
    </style>
    <style name="TextAppearance.AppCompat.Widget.Switch" parent="Base.TextAppearance.AppCompat.Widget.Switch"/>
    <style name="TextAppearance.AppCompat.Widget.TextView.SpinnerItem" parent="Base.TextAppearance.AppCompat.Widget.TextView.SpinnerItem"/>
    <style name="TextAppearance.StatusBar.EventContent" parent=""/>
    <style name="TextAppearance.StatusBar.EventContent.Info" parent=""/>
    <style name="TextAppearance.StatusBar.EventContent.Line2" parent=""/>
    <style name="TextAppearance.StatusBar.EventContent.Time" parent=""/>
    <style name="TextAppearance.StatusBar.EventContent.Title" parent=""/>
    <style name="TextAppearance.Widget.AppCompat.ExpandedMenu.Item" parent="Base.TextAppearance.Widget.AppCompat.ExpandedMenu.Item">
    </style>
    <style name="TextAppearance.Widget.AppCompat.Toolbar.Subtitle" parent="Base.TextAppearance.Widget.AppCompat.Toolbar.Subtitle">
    </style>
    <style name="TextAppearance.Widget.AppCompat.Toolbar.Title" parent="Base.TextAppearance.Widget.AppCompat.Toolbar.Title">
    </style>
    <style name="Theme.AppCompat" parent="Base.Theme.AppCompat"/>
    <style name="Theme.AppCompat.CompactMenu" parent="Base.Theme.AppCompat.CompactMenu"/>
    <style name="Theme.AppCompat.DayNight" parent="Theme.AppCompat.Light"/>
    <style name="Theme.AppCompat.DayNight.DarkActionBar" parent="Theme.AppCompat.Light.DarkActionBar"/>
    <style name="Theme.AppCompat.DayNight.Dialog" parent="Theme.AppCompat.Light.Dialog"/>
    <style name="Theme.AppCompat.DayNight.Dialog.Alert" parent="Theme.AppCompat.Light.Dialog.Alert"/>
    <style name="Theme.AppCompat.DayNight.Dialog.MinWidth" parent="Theme.AppCompat.Light.Dialog.MinWidth"/>
    <style name="Theme.AppCompat.DayNight.DialogWhenLarge" parent="Theme.AppCompat.Light.DialogWhenLarge"/>
    <style name="Theme.AppCompat.DayNight.NoActionBar" parent="Theme.AppCompat.Light.NoActionBar"/>
    <style name="Theme.AppCompat.Dialog" parent="Base.Theme.AppCompat.Dialog"/>
    <style name="Theme.AppCompat.Dialog.Alert" parent="Base.Theme.AppCompat.Dialog.Alert"/>
    <style name="Theme.AppCompat.Dialog.MinWidth" parent="Base.Theme.AppCompat.Dialog.MinWidth"/>
    <style name="Theme.AppCompat.DialogWhenLarge" parent="Base.Theme.AppCompat.DialogWhenLarge">
    </style>
    <style name="Theme.AppCompat.Light" parent="Base.Theme.AppCompat.Light"/>
    <style name="Theme.AppCompat.Light.DarkActionBar" parent="Base.Theme.AppCompat.Light.DarkActionBar"/>
    <style name="Theme.AppCompat.Light.Dialog" parent="Base.Theme.AppCompat.Light.Dialog"/>
    <style name="Theme.AppCompat.Light.Dialog.Alert" parent="Base.Theme.AppCompat.Light.Dialog.Alert"/>
    <style name="Theme.AppCompat.Light.Dialog.MinWidth" parent="Base.Theme.AppCompat.Light.Dialog.MinWidth"/>
    <style name="Theme.AppCompat.Light.DialogWhenLarge" parent="Base.Theme.AppCompat.Light.DialogWhenLarge">
    </style>
    <style name="Theme.AppCompat.Light.NoActionBar">
        <item name="windowActionBar">false</item>
        <item name="windowNoTitle">true</item>
    </style>
    <style name="Theme.AppCompat.NoActionBar">
        <item name="windowActionBar">false</item>
        <item name="windowNoTitle">true</item>
    </style>
    <style name="ThemeOverlay.AppCompat" parent="Base.ThemeOverlay.AppCompat"/>
    <style name="ThemeOverlay.AppCompat.ActionBar" parent="Base.ThemeOverlay.AppCompat.ActionBar"/>
    <style name="ThemeOverlay.AppCompat.Dark" parent="Base.ThemeOverlay.AppCompat.Dark"/>
    <style name="ThemeOverlay.AppCompat.Dark.ActionBar" parent="Base.ThemeOverlay.AppCompat.Dark.ActionBar"/>
    <style name="ThemeOverlay.AppCompat.Light" parent="Base.ThemeOverlay.AppCompat.Light"/>
    <style name="Widget.AppCompat.ActionBar" parent="Base.Widget.AppCompat.ActionBar">
    </style>
    <style name="Widget.AppCompat.ActionBar.Solid" parent="Base.Widget.AppCompat.ActionBar.Solid">
    </style>
    <style name="Widget.AppCompat.ActionBar.TabBar" parent="Base.Widget.AppCompat.ActionBar.TabBar">
    </style>
    <style name="Widget.AppCompat.ActionBar.TabText" parent="Base.Widget.AppCompat.ActionBar.TabText">
    </style>
    <style name="Widget.AppCompat.ActionBar.TabView" parent="Base.Widget.AppCompat.ActionBar.TabView">
    </style>
    <style name="Widget.AppCompat.ActionButton" parent="Base.Widget.AppCompat.ActionButton"/>
    <style name="Widget.AppCompat.ActionButton.CloseMode" parent="Base.Widget.AppCompat.ActionButton.CloseMode"/>
    <style name="Widget.AppCompat.ActionButton.Overflow" parent="Base.Widget.AppCompat.ActionButton.Overflow"/>
    <style name="Widget.AppCompat.ActionMode" parent="Base.Widget.AppCompat.ActionMode">
    </style>
    <style name="Widget.AppCompat.ActivityChooserView" parent="Base.Widget.AppCompat.ActivityChooserView">
    </style>
    <style name="Widget.AppCompat.AutoCompleteTextView" parent="Base.Widget.AppCompat.AutoCompleteTextView">
    </style>
    <style name="Widget.AppCompat.Button" parent="Base.Widget.AppCompat.Button"/>
    <style name="Widget.AppCompat.Button.Borderless" parent="Base.Widget.AppCompat.Button.Borderless"/>
    <style name="Widget.AppCompat.Button.Borderless.Colored" parent="Base.Widget.AppCompat.Button.Borderless.Colored"/>
    <style name="Widget.AppCompat.Button.ButtonBar.AlertDialog" parent="Base.Widget.AppCompat.Button.ButtonBar.AlertDialog"/>
    <style name="Widget.AppCompat.Button.Colored" parent="Base.Widget.AppCompat.Button.Colored"/>
    <style name="Widget.AppCompat.Button.Small" parent="Base.Widget.AppCompat.Button.Small"/>
    <style name="Widget.AppCompat.ButtonBar" parent="Base.Widget.AppCompat.ButtonBar"/>
    <style name="Widget.AppCompat.ButtonBar.AlertDialog" parent="Base.Widget.AppCompat.ButtonBar.AlertDialog"/>
    <style name="Widget.AppCompat.CompoundButton.CheckBox" parent="Base.Widget.AppCompat.CompoundButton.CheckBox"/>
    <style name="Widget.AppCompat.CompoundButton.RadioButton" parent="Base.Widget.AppCompat.CompoundButton.RadioButton"/>
    <style name="Widget.AppCompat.CompoundButton.Switch" parent="Base.Widget.AppCompat.CompoundButton.Switch"/>
    <style name="Widget.AppCompat.DrawerArrowToggle" parent="Base.Widget.AppCompat.DrawerArrowToggle">
        <item name="color">?attr/colorControlNormal</item>
    </style>
    <style name="Widget.AppCompat.DropDownItem.Spinner" parent="RtlOverlay.Widget.AppCompat.Search.DropDown.Text"/>
    <style name="Widget.AppCompat.EditText" parent="Base.Widget.AppCompat.EditText"/>
    <style name="Widget.AppCompat.ImageButton" parent="Base.Widget.AppCompat.ImageButton"/>
    <style name="Widget.AppCompat.Light.ActionBar" parent="Base.Widget.AppCompat.Light.ActionBar">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.Solid" parent="Base.Widget.AppCompat.Light.ActionBar.Solid">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.Solid.Inverse"/>
    <style name="Widget.AppCompat.Light.ActionBar.TabBar" parent="Base.Widget.AppCompat.Light.ActionBar.TabBar">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.TabBar.Inverse"/>
    <style name="Widget.AppCompat.Light.ActionBar.TabText" parent="Base.Widget.AppCompat.Light.ActionBar.TabText">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.TabText.Inverse" parent="Base.Widget.AppCompat.Light.ActionBar.TabText.Inverse">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.TabView" parent="Base.Widget.AppCompat.Light.ActionBar.TabView">
    </style>
    <style name="Widget.AppCompat.Light.ActionBar.TabView.Inverse"/>
    <style name="Widget.AppCompat.Light.ActionButton" parent="Widget.AppCompat.ActionButton"/>
    <style name="Widget.AppCompat.Light.ActionButton.CloseMode" parent="Widget.AppCompat.ActionButton.CloseMode"/>
    <style name="Widget.AppCompat.Light.ActionButton.Overflow" parent="Widget.AppCompat.ActionButton.Overflow"/>
    <style name="Widget.AppCompat.Light.ActionMode.Inverse" parent="Widget.AppCompat.ActionMode"/>
    <style name="Widget.AppCompat.Light.ActivityChooserView" parent="Widget.AppCompat.ActivityChooserView"/>
    <style name="Widget.AppCompat.Light.AutoCompleteTextView" parent="Widget.AppCompat.AutoCompleteTextView"/>
    <style name="Widget.AppCompat.Light.DropDownItem.Spinner" parent="Widget.AppCompat.DropDownItem.Spinner"/>
    <style name="Widget.AppCompat.Light.ListPopupWindow" parent="Widget.AppCompat.ListPopupWindow"/>
    <style name="Widget.AppCompat.Light.ListView.DropDown" parent="Widget.AppCompat.ListView.DropDown"/>
    <style name="Widget.AppCompat.Light.PopupMenu" parent="Base.Widget.AppCompat.Light.PopupMenu">
    </style>
    <style name="Widget.AppCompat.Light.PopupMenu.Overflow" parent="Base.Widget.AppCompat.Light.PopupMenu.Overflow">
    </style>
    <style name="Widget.AppCompat.Light.SearchView" parent="Widget.AppCompat.SearchView"/>
    <style name="Widget.AppCompat.Light.Spinner.DropDown.ActionBar" parent="Widget.AppCompat.Spinner.DropDown.ActionBar"/>
    <style name="Widget.AppCompat.ListPopupWindow" parent="Base.Widget.AppCompat.ListPopupWindow">
    </style>
    <style name="Widget.AppCompat.ListView" parent="Base.Widget.AppCompat.ListView"/>
    <style name="Widget.AppCompat.ListView.DropDown" parent="Base.Widget.AppCompat.ListView.DropDown"/>
    <style name="Widget.AppCompat.ListView.Menu" parent="Base.Widget.AppCompat.ListView.Menu">
    </style>
    <style name="Widget.AppCompat.PopupMenu" parent="Base.Widget.AppCompat.PopupMenu">
    </style>
    <style name="Widget.AppCompat.PopupMenu.Overflow" parent="Base.Widget.AppCompat.PopupMenu.Overflow">
    </style>
    <style name="Widget.AppCompat.PopupWindow" parent="Base.Widget.AppCompat.PopupWindow">
    </style>
    <style name="Widget.AppCompat.ProgressBar" parent="Base.Widget.AppCompat.ProgressBar">
    </style>
    <style name="Widget.AppCompat.ProgressBar.Horizontal" parent="Base.Widget.AppCompat.ProgressBar.Horizontal">
    </style>
    <style name="Widget.AppCompat.RatingBar" parent="Base.Widget.AppCompat.RatingBar"/>
    <style name="Widget.AppCompat.RatingBar.Indicator" parent="Base.Widget.AppCompat.RatingBar.Indicator"/>
    <style name="Widget.AppCompat.RatingBar.Small" parent="Base.Widget.AppCompat.RatingBar.Small"/>
    <style name="Widget.AppCompat.SearchView" parent="Base.Widget.AppCompat.SearchView"/>
    <style name="Widget.AppCompat.SearchView.ActionBar" parent="Base.Widget.AppCompat.SearchView.ActionBar"/>
    <style name="Widget.AppCompat.SeekBar" parent="Base.Widget.AppCompat.SeekBar"/>
    <style name="Widget.AppCompat.Spinner" parent="Base.Widget.AppCompat.Spinner"/>
    <style name="Widget.AppCompat.Spinner.DropDown"/>
    <style name="Widget.AppCompat.Spinner.DropDown.ActionBar"/>
    <style name="Widget.AppCompat.Spinner.Underlined" parent="Base.Widget.AppCompat.Spinner.Underlined"/>
    <style name="Widget.AppCompat.TextView.SpinnerItem" parent="Base.Widget.AppCompat.TextView.SpinnerItem"/>
    <style name="Widget.AppCompat.Toolbar" parent="Base.Widget.AppCompat.Toolbar"/>
    <style name="Widget.AppCompat.Toolbar.Button.Navigation" parent="Base.Widget.AppCompat.Toolbar.Button.Navigation"/>
</resources>
