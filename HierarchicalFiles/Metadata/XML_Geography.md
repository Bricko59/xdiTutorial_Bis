<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_ZWh_8D80Ee2HIsvGuwi14w" name="geography" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_ZWj1ID80Ee2HIsvGuwi14w" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_uCIsUT80Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_In/Xml/geography.xml"/>
  <node defType="com.stambia.xml.root" id="_uCIFRT80Ee2HIsvGuwi14w" name="geography">
    <attribute defType="com.stambia.xml.root.originalType" id="_uCIFRj80Ee2HIsvGuwi14w" value="geo:geography"/>
    <node defType="com.stambia.xml.sequence" id="_uCIFRz80Ee2HIsvGuwi14w">
      <attribute defType="com.stambia.xml.sequence.position" id="_uCIFSD80Ee2HIsvGuwi14w" value="0"/>
      <node defType="com.stambia.xml.element" id="_uCIFST80Ee2HIsvGuwi14w" name="state">
        <attribute defType="com.stambia.xml.element.originalType" id="_uCIFSj80Ee2HIsvGuwi14w" value="state"/>
        <attribute defType="com.stambia.xml.element.minOccurs" id="_uCIFSz80Ee2HIsvGuwi14w" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_uCIFTD80Ee2HIsvGuwi14w" value="-1"/>
        <node defType="com.stambia.xml.attribute" id="_uCIFTT80Ee2HIsvGuwi14w" name="stateName">
          <attribute defType="com.stambia.xml.attribute.type" id="_uCIFTj80Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_uCIFTz80Ee2HIsvGuwi14w" value="0"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_uCIFUD80Ee2HIsvGuwi14w" name="upperCaseName">
          <attribute defType="com.stambia.xml.attribute.type" id="_uCIFUT80Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_uCIFUj80Ee2HIsvGuwi14w" value="1"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_uCIFUz80Ee2HIsvGuwi14w" name="code">
          <attribute defType="com.stambia.xml.attribute.type" id="_uCIFVD80Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.position" id="_uCIFVT80Ee2HIsvGuwi14w" value="2"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_uCIFVj80Ee2HIsvGuwi14w">
          <attribute defType="com.stambia.xml.sequence.position" id="_uCIFVz80Ee2HIsvGuwi14w" value="0"/>
          <node defType="com.stambia.xml.element" id="_uCIFWD80Ee2HIsvGuwi14w" name="city">
            <attribute defType="com.stambia.xml.element.originalType" id="_uCIFWT80Ee2HIsvGuwi14w" value="city"/>
            <attribute defType="com.stambia.xml.element.minOccurs" id="_uCIFWj80Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_uCIFWz80Ee2HIsvGuwi14w" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_uCIFXD80Ee2HIsvGuwi14w" name="zipCode">
              <attribute defType="com.stambia.xml.attribute.type" id="_uCIFXT80Ee2HIsvGuwi14w" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_uCIFXj80Ee2HIsvGuwi14w" value="0"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_uCIFXz80Ee2HIsvGuwi14w" name="cityName">
              <attribute defType="com.stambia.xml.attribute.type" id="_uCIFYD80Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_uCIFYT80Ee2HIsvGuwi14w" value="1"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.xml.namespace" id="_uCIFYj80Ee2HIsvGuwi14w" name="http://stambia.org/samples/geography">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_uCIFYz80Ee2HIsvGuwi14w" value="geo"/>
  </node>
</md:node>