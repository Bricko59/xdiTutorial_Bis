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
  </node>
</md:node>