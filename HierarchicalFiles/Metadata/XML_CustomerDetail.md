<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_cO3a0D87Ee2HIsvGuwi14w" name="customerDetails" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_cO5QAD87Ee2HIsvGuwi14w" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_mnXgKz87Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_In/Xml/customerDetails.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_mnXgLT87Ee2HIsvGuwi14w" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_mnXgLj87Ee2HIsvGuwi14w" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_mnXgLz87Ee2HIsvGuwi14w" value="http://semarchy.com/samples/management"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_uMxK0D87Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_Out/Xml/customerDetails.xml"/>
  <node defType="com.stambia.xml.namespace" id="_mnXfuD87Ee2HIsvGuwi14w" name="http://semarchy.com/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_mnXfuT87Ee2HIsvGuwi14w" value="com"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_mnXfuj87Ee2HIsvGuwi14w" name="http://semarchy.com/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_mnXfuz87Ee2HIsvGuwi14w" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_mnXfvD87Ee2HIsvGuwi14w" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_mnXfvT87Ee2HIsvGuwi14w" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="_mnXfvj87Ee2HIsvGuwi14w" name="customerDetails" position="0">
    <node defType="com.stambia.xml.sequence" id="_mnXfvz87Ee2HIsvGuwi14w" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_mnXfwD87Ee2HIsvGuwi14w" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_mnXfwT87Ee2HIsvGuwi14w" value="1"/>
      <node defType="com.stambia.xml.element" id="_mnXfwj87Ee2HIsvGuwi14w" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_mnXfwz87Ee2HIsvGuwi14w" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_mnXfxD87Ee2HIsvGuwi14w" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_mnXfxT87Ee2HIsvGuwi14w" value="mgt:CustomerDetail"/>
        <node defType="com.stambia.xml.attribute" id="_mnXfxj87Ee2HIsvGuwi14w" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXfxz87Ee2HIsvGuwi14w" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXfyD87Ee2HIsvGuwi14w" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXfyT87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXfyj87Ee2HIsvGuwi14w" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXfyz87Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXfzD87Ee2HIsvGuwi14w" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXfzT87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXfzj87Ee2HIsvGuwi14w" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXfzz87Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf0D87Ee2HIsvGuwi14w" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXf0T87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXf0j87Ee2HIsvGuwi14w" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXf0z87Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf1D87Ee2HIsvGuwi14w" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXf1T87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXf1j87Ee2HIsvGuwi14w" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXf1z87Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf2D87Ee2HIsvGuwi14w" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXf2T87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXf2j87Ee2HIsvGuwi14w" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXf2z87Ee2HIsvGuwi14w" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf3D87Ee2HIsvGuwi14w" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXf3T87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_mnXf3j87Ee2HIsvGuwi14w" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="_mnXf3z87Ee2HIsvGuwi14w" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf4D87Ee2HIsvGuwi14w" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_mnXf4T87Ee2HIsvGuwi14w" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_mnXf4j87Ee2HIsvGuwi14w" position="10">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_mnXf4z87Ee2HIsvGuwi14w" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_mnXf5D87Ee2HIsvGuwi14w" value="1"/>
          <node defType="com.stambia.xml.element" id="_mnXf5T87Ee2HIsvGuwi14w" name="address" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_mnXf5j87Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_mnXf5z87Ee2HIsvGuwi14w" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_mnXf6D87Ee2HIsvGuwi14w" value="com:Address"/>
            <node defType="com.stambia.xml.attribute" id="_mnXf6T87Ee2HIsvGuwi14w" name="addressId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXf6j87Ee2HIsvGuwi14w" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf6z87Ee2HIsvGuwi14w" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXf7D87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXf7T87Ee2HIsvGuwi14w" name="addressDetails" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXf7j87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf7z87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXf8D87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXf8T87Ee2HIsvGuwi14w" name="zipCode" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXf8j87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf8z87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXf9D87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXf9T87Ee2HIsvGuwi14w" name="city" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXf9j87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf9z87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXf-D87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXf-T87Ee2HIsvGuwi14w" name="stateCode" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXf-j87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXf-z87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXf_D87Ee2HIsvGuwi14w" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_mnXf_T87Ee2HIsvGuwi14w" name="phone" position="1">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_mnXf_j87Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_mnXf_z87Ee2HIsvGuwi14w" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_mnXgAD87Ee2HIsvGuwi14w" value="com:Phone"/>
            <node defType="com.stambia.xml.attribute" id="_mnXgAT87Ee2HIsvGuwi14w" name="phoneId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgAj87Ee2HIsvGuwi14w" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgAz87Ee2HIsvGuwi14w" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgBD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgBT87Ee2HIsvGuwi14w" name="phoneTypeCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgBj87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgBz87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgCD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgCT87Ee2HIsvGuwi14w" name="phoneNumber" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgCj87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgCz87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgDD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgDT87Ee2HIsvGuwi14w" name="phoneType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgDj87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgDz87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgED87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgET87Ee2HIsvGuwi14w" name="phoningAllowed" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgEj87Ee2HIsvGuwi14w" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgEz87Ee2HIsvGuwi14w" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgFD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="_mnXgFT87Ee2HIsvGuwi14w" name="email" position="2">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_mnXgFj87Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_mnXgFz87Ee2HIsvGuwi14w" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_mnXgGD87Ee2HIsvGuwi14w" value="com:Email"/>
            <node defType="com.stambia.xml.attribute" id="_mnXgGT87Ee2HIsvGuwi14w" name="emailId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgGj87Ee2HIsvGuwi14w" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgGz87Ee2HIsvGuwi14w" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgHD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgHT87Ee2HIsvGuwi14w" name="emailAddress" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgHj87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgHz87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgID87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgIT87Ee2HIsvGuwi14w" name="emailType" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgIj87Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgIz87Ee2HIsvGuwi14w" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgJD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_mnXgJT87Ee2HIsvGuwi14w" name="mailingAllowed" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="_mnXgJj87Ee2HIsvGuwi14w" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_mnXgJz87Ee2HIsvGuwi14w" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_mnXgKD87Ee2HIsvGuwi14w" value="optional"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>