<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_PA9NwD44Ee27Rbg9YrGf1Q" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_PETcsD44Ee27Rbg9YrGf1Q" name="References_Files">
    <attribute defType="com.stambia.file.directory.path" id="_PEgRAD44Ee27Rbg9YrGf1Q" value="%{env:workspace_loc}%/Training/Files_In/Reference_Files"/>
    <node defType="com.stambia.file.file" id="_PEiGMD44Ee27Rbg9YrGf1Q" name="discount_range">
      <attribute defType="com.stambia.file.file.type" id="_PGGMcT44Ee27Rbg9YrGf1Q" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_PGGMcz44Ee27Rbg9YrGf1Q" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_PGGMdD44Ee27Rbg9YrGf1Q" value="2C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_PGGMdj44Ee27Rbg9YrGf1Q" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_PGGMeD44Ee27Rbg9YrGf1Q" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_PGGMeT44Ee27Rbg9YrGf1Q" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_PGGMej44Ee27Rbg9YrGf1Q" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_tBqoUD44Ee27Rbg9YrGf1Q" value="DiscountRanges.txt"/>
      <node defType="com.stambia.file.field" id="_vPLBsD44Ee27Rbg9YrGf1Q" name="min" position="1">
        <attribute defType="com.stambia.file.field.size" id="_vPLBsT44Ee27Rbg9YrGf1Q" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_vPLBsj44Ee27Rbg9YrGf1Q" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_vPLBsz44Ee27Rbg9YrGf1Q" value="MIN"/>
      </node>
      <node defType="com.stambia.file.field" id="_vPLBuD44Ee27Rbg9YrGf1Q" name="range" position="3">
        <attribute defType="com.stambia.file.field.size" id="_vPLBuT44Ee27Rbg9YrGf1Q" value="62"/>
        <attribute defType="com.stambia.file.field.type" id="_vPLBuj44Ee27Rbg9YrGf1Q" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_vPLBuz44Ee27Rbg9YrGf1Q" value="RANGE"/>
      </node>
      <node defType="com.stambia.file.field" id="_vPLBtD44Ee27Rbg9YrGf1Q" name="max" position="2">
        <attribute defType="com.stambia.file.field.size" id="_vPLBtT44Ee27Rbg9YrGf1Q" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_vPLBtj44Ee27Rbg9YrGf1Q" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_vPLBtz44Ee27Rbg9YrGf1Q" value="MAX"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_KBAe8D5ZEe2HIsvGuwi14w" name="Time">
      <attribute defType="com.stambia.file.file.type" id="_KB8TED5ZEe2HIsvGuwi14w" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_KB-IQD5ZEe2HIsvGuwi14w" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_KB-IQT5ZEe2HIsvGuwi14w" value="3B"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_KB-vUD5ZEe2HIsvGuwi14w" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_KB_WYD5ZEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_KB_WYT5ZEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_KB_WYj5ZEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_RGKjwD5ZEe2HIsvGuwi14w" value="Time.csv"/>
      <node defType="com.stambia.file.field" id="_TOe7ID5ZEe2HIsvGuwi14w" name="day_date" position="1">
        <attribute defType="com.stambia.file.field.size" id="_TOe7IT5ZEe2HIsvGuwi14w" value="66"/>
        <attribute defType="com.stambia.file.field.type" id="_TOe7Ij5ZEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_TOe7Iz5ZEe2HIsvGuwi14w" value="F1"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_UrnyED5aEe2HIsvGuwi14w" name="us_states">
      <attribute defType="com.stambia.file.file.type" id="_Ur-XYD5aEe2HIsvGuwi14w" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_Ur_lgT5aEe2HIsvGuwi14w" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_Ur_lgj5aEe2HIsvGuwi14w" value="2C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_UsAMkD5aEe2HIsvGuwi14w" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_UsAMkj5aEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_UsAzoD5aEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_UsAzoT5aEe2HIsvGuwi14w" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_Z6xXgD5aEe2HIsvGuwi14w" value="REF_US_STATES.csv"/>
      <node defType="com.stambia.file.field" id="_dF4ooD5aEe2HIsvGuwi14w" name="STATE_UPPER_CASE" position="1">
        <attribute defType="com.stambia.file.field.size" id="_dF4ooT5aEe2HIsvGuwi14w" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_dF4ooj5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_dF4ooz5aEe2HIsvGuwi14w" value="STATE_UPPER_CASE"/>
      </node>
      <node defType="com.stambia.file.field" id="_dF4oqD5aEe2HIsvGuwi14w" name="STATE_CODE" position="3">
        <attribute defType="com.stambia.file.field.size" id="_dF4oqT5aEe2HIsvGuwi14w" value="52"/>
        <attribute defType="com.stambia.file.field.type" id="_dF4oqj5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_dF4oqz5aEe2HIsvGuwi14w" value="STATE_CODE"/>
      </node>
      <node defType="com.stambia.file.field" id="_dF4opD5aEe2HIsvGuwi14w" name="STATE" position="2">
        <attribute defType="com.stambia.file.field.size" id="_dF4opT5aEe2HIsvGuwi14w" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_dF4opj5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_dF4opz5aEe2HIsvGuwi14w" value="STATE"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_gWalQD5aEe2HIsvGuwi14w" name="us_cities">
      <attribute defType="com.stambia.file.file.type" id="_gWxxoD5aEe2HIsvGuwi14w" value="POSITIONAL"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_gWxxoj5aEe2HIsvGuwi14w" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_gWxxoz5aEe2HIsvGuwi14w" value="3B"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_gWxxpT5aEe2HIsvGuwi14w" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_gWxxpz5aEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_gWxxqD5aEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_gWxxqT5aEe2HIsvGuwi14w" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_kUWacD5aEe2HIsvGuwi14w" value="ref_us_cities.txt"/>
      <node defType="com.stambia.file.field" id="_yeI_oD5aEe2HIsvGuwi14w" name="ZIP_CODE" position="1">
        <attribute defType="com.stambia.file.field.size" id="_yeI_oT5aEe2HIsvGuwi14w" value="5"/>
        <attribute defType="com.stambia.file.field.type" id="_yeI_oj5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_yeI_oz5aEe2HIsvGuwi14w" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_5sOW8D5aEe2HIsvGuwi14w" name="CITY" position="6">
        <attribute defType="com.stambia.file.field.physicalName" id="_5sVEoD5aEe2HIsvGuwi14w" value="C2"/>
        <attribute defType="com.stambia.file.field.type" id="_5sVEoT5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_5sVEoj5aEe2HIsvGuwi14w" value="72"/>
      </node>
      <node defType="com.stambia.file.field" id="_7ruwkD5aEe2HIsvGuwi14w" name="STATE_CODE" position="78">
        <attribute defType="com.stambia.file.field.physicalName" id="_7rvXoD5aEe2HIsvGuwi14w" value="F2"/>
        <attribute defType="com.stambia.file.field.type" id="_7rvXoT5aEe2HIsvGuwi14w" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_7rvXoj5aEe2HIsvGuwi14w" value="10"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.file.directory" id="_IIXdED8vEe2HIsvGuwi14w" name="Statistic_Report_Folder">
    <attribute defType="com.stambia.file.directory.path" id="_IIjqUD8vEe2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_Out/Statistic_Report"/>
  </node>
</md:node>