# Android-Guidelines
##### This file contains some example of coding guidelines for android/java


### Version (1.3)


### 1. Package Name 
##### `com.client.Appname`

### 2. Package Structure

##### src
  * `com.client.appname.app`              - contain Application classes only
  * `com.client.appname.utils`            - contain utils and misc classes
   
### 3. Naming convention for Xml files
### we follow `<WHAT_WHERE_DESCRIPTION_SIZE>` standrad
* ### _Layout.xml_  
  ###### `<what>_<where>  <component name>_<where to used in>` 
  ######  Example : 
  `activity_main`   `activity_article`   `fragment_ArticleDetail` `FontTextView_articleReader`

* ### _Strings.xml_
  ###### we follow `<WHERE_DESCRIPTION>` 
  ###### Example : 
  ###### `article_title` `artilce_back`
  ###### in case using string in all app  example `all_ok`  `all_cancel`

* ### _drawable.xml_ 
  ###### we follow `<WHERE_DESCRIPTION_SIZE` <Size> Optional
  ###### Example : `article_previous_small` `article_previous_24dp` `article_startReading_medium` 

* ### _IDs.xml_
  ###### we follow `<WHAT_WHERE_DESCRIPTION>` 
  ###### Example : 
  ###### `textview_article_title` `imageButton_artilce_back`    `linearlayout_mainArticle_fragmentContainer`


* ### _Dimensions.xml_
  ###### we follow `<WHAT_WHERE_DESCRIPTION_SIZE>` <Size> Optional
  ###### Example : 
  ###### `textSize_articleMain_title_Medium` `margin_artilceMain_background_72dp` `width_all_articleDetail`


### 4. Constants
* ###### we follow `<WHERE_DESCRIPTION>`
* ###### Example : 

     `PARAMS.LOGIN_EMAIL` `BUNDLES.INTRO_FRAGMENT_TEXT`
 
 #### 
 ####
 ```javascript
   public interface Constants {
   interface BUNDLE {}  // All constants related to Intent operations.
   interface PARAMS {}  // All constants related to Server Parameters.
   interface PREFS {}   // All constants related to Preferences.
   interface URL {}     // All cibstants related to urls.
   } 
   ```
   
### 5. Views Variable
*  we follow `<DESCRIPTION_WHAT>`
*  Example : 

```javascript
    EditText phoneNumberEditText;
    ImageView profileImageView;
    EditText emailEditText;
```


