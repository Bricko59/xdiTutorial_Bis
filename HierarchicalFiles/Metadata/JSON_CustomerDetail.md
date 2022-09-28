<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.json.schema" id="_L25jUD86Ee2HIsvGuwi14w" md:ref="resource.tech#UUID_TECH_JSON1?fileId=UUID_TECH_JSON1$type=tech$name=json?" internalVersion="v1.0.0">
  <node defType="com.stambia.json.rootObject" id="_L9xAUD86Ee2HIsvGuwi14w" name="CustomerDetail">
    <attribute defType="com.stambia.json.rootObject.encoding" id="_L990oD86Ee2HIsvGuwi14w" value="UTF-8"/>
    <attribute defType="com.stambia.json.rootObject.reverseFilePath" id="_L-CtID86Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_In/Json/customer.json"/>
    <attribute defType="com.stambia.json.rootObject.filePath" id="_XrTJAD87Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_Out/Json/customerDetails.json"/>
    <node defType="com.stambia.json.value" id="_mA2HtT86Ee2HIsvGuwi14w" name="firstName" position="1">
      <attribute defType="com.stambia.json.value.type" id="_mA2Htj86Ee2HIsvGuwi14w" value="string"/>
    </node>
    <node defType="com.stambia.json.value" id="_mA2Htz86Ee2HIsvGuwi14w" name="lastName" position="2">
      <attribute defType="com.stambia.json.value.type" id="_mA2HuD86Ee2HIsvGuwi14w" value="string"/>
    </node>
    <node defType="com.stambia.json.value" id="_mA2HuT86Ee2HIsvGuwi14w" name="birthday" position="3">
      <attribute defType="com.stambia.json.value.type" id="_mA2Huj86Ee2HIsvGuwi14w" value="string"/>
    </node>
    <node defType="com.stambia.json.object" id="_mA2Huz86Ee2HIsvGuwi14w" name="address" position="4">
      <node defType="com.stambia.json.value" id="_mA2HvD86Ee2HIsvGuwi14w" name="streetAddress" position="1">
        <attribute defType="com.stambia.json.value.type" id="_mA2HvT86Ee2HIsvGuwi14w" value="string"/>
      </node>
      <node defType="com.stambia.json.value" id="_mA2Hvj86Ee2HIsvGuwi14w" name="city" position="2">
        <attribute defType="com.stambia.json.value.type" id="_mA2Hvz86Ee2HIsvGuwi14w" value="string"/>
      </node>
      <node defType="com.stambia.json.value" id="_mA2HwD86Ee2HIsvGuwi14w" name="state" position="3">
        <attribute defType="com.stambia.json.value.type" id="_mA2HwT86Ee2HIsvGuwi14w" value="string"/>
      </node>
      <node defType="com.stambia.json.value" id="_mA2Hwj86Ee2HIsvGuwi14w" name="postalCode" position="4">
        <attribute defType="com.stambia.json.value.type" id="_mA2Hwz86Ee2HIsvGuwi14w" value="string"/>
      </node>
    </node>
    <node defType="com.stambia.json.array" id="_mA2HxD86Ee2HIsvGuwi14w" name="phoneNumber" position="5">
      <node defType="com.stambia.json.object" id="_mA2HxT86Ee2HIsvGuwi14w" name="item" position="1">
        <node defType="com.stambia.json.value" id="_mA2Hxj86Ee2HIsvGuwi14w" name="type" position="1">
          <attribute defType="com.stambia.json.value.type" id="_mA2Hxz86Ee2HIsvGuwi14w" value="string"/>
        </node>
        <node defType="com.stambia.json.value" id="_mA2HyD86Ee2HIsvGuwi14w" name="number" position="2">
          <attribute defType="com.stambia.json.value.type" id="_mA2HyT86Ee2HIsvGuwi14w" value="string"/>
        </node>
      </node>
    </node>
  </node>
</md:node>