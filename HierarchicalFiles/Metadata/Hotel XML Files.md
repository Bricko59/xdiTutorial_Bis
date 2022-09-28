<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_qpttED82Ee2HIsvGuwi14w" name="marketingCampaign" md:ref="resource.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_qpviQD82Ee2HIsvGuwi14w" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_BJJukD83Ee2HIsvGuwi14w" value="%{env:workspace_loc}%/Training/Files_In/Xml/marketingCampaign.xml"/>
  <node defType="com.stambia.xml.root" id="_BJJHhT83Ee2HIsvGuwi14w" name="marketingCampaign">
    <attribute defType="com.stambia.xml.root.originalType" id="_BJJHhj83Ee2HIsvGuwi14w" value="mgt:marketingCampaign"/>
    <node defType="com.stambia.xml.sequence" id="_BJJHhz83Ee2HIsvGuwi14w">
      <attribute defType="com.stambia.xml.sequence.position" id="_BJJHiD83Ee2HIsvGuwi14w" value="0"/>
      <node defType="com.stambia.xml.element" id="_BJJHiT83Ee2HIsvGuwi14w" name="phoningCampaign">
        <attribute defType="com.stambia.xml.element.originalType" id="_BJJHij83Ee2HIsvGuwi14w" value="phoningCampaign"/>
        <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJHiz83Ee2HIsvGuwi14w" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJHjD83Ee2HIsvGuwi14w" value="1"/>
        <node defType="com.stambia.xml.sequence" id="_BJJHjT83Ee2HIsvGuwi14w">
          <attribute defType="com.stambia.xml.sequence.position" id="_BJJHjj83Ee2HIsvGuwi14w" value="0"/>
          <node defType="com.stambia.xml.element" id="_BJJHjz83Ee2HIsvGuwi14w" name="customer">
            <attribute defType="com.stambia.xml.element.originalType" id="_BJJHkD83Ee2HIsvGuwi14w" value="customer"/>
            <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJHkT83Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJHkj83Ee2HIsvGuwi14w" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_BJJHkz83Ee2HIsvGuwi14w" name="lastName">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHlD83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHlT83Ee2HIsvGuwi14w" value="0"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHlj83Ee2HIsvGuwi14w" name="titleCode">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHlz83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHmD83Ee2HIsvGuwi14w" value="1"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHmT83Ee2HIsvGuwi14w" name="title">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHmj83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHmz83Ee2HIsvGuwi14w" value="2"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHnD83Ee2HIsvGuwi14w" name="customerId">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHnT83Ee2HIsvGuwi14w" value="byte"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHnj83Ee2HIsvGuwi14w" value="3"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHnz83Ee2HIsvGuwi14w" name="company">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHoD83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHoT83Ee2HIsvGuwi14w" value="4"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHoj83Ee2HIsvGuwi14w" name="birthDate">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHoz83Ee2HIsvGuwi14w" value="date"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHpD83Ee2HIsvGuwi14w" value="5"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHpT83Ee2HIsvGuwi14w" name="firstName">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHpj83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHpz83Ee2HIsvGuwi14w" value="6"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_BJJHqD83Ee2HIsvGuwi14w">
              <attribute defType="com.stambia.xml.sequence.position" id="_BJJHqT83Ee2HIsvGuwi14w" value="0"/>
              <node defType="com.stambia.xml.element" id="_BJJHqj83Ee2HIsvGuwi14w" name="phone">
                <attribute defType="com.stambia.xml.element.originalType" id="_BJJHqz83Ee2HIsvGuwi14w" value="phone"/>
                <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJHrD83Ee2HIsvGuwi14w" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJHrT83Ee2HIsvGuwi14w" value="-1"/>
                <node defType="com.stambia.xml.attribute" id="_BJJHrj83Ee2HIsvGuwi14w" name="phoneNumber">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJHrz83Ee2HIsvGuwi14w" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJHsD83Ee2HIsvGuwi14w" value="0"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJHsT83Ee2HIsvGuwi14w" name="phoneType">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJHsj83Ee2HIsvGuwi14w" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJHsz83Ee2HIsvGuwi14w" value="1"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJHtD83Ee2HIsvGuwi14w" name="phoningAllowed">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJHtT83Ee2HIsvGuwi14w" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJHtj83Ee2HIsvGuwi14w" value="2"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJHtz83Ee2HIsvGuwi14w" name="phoneId">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJHuD83Ee2HIsvGuwi14w" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJHuT83Ee2HIsvGuwi14w" value="3"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJHuj83Ee2HIsvGuwi14w" name="phoneTypeCode">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJHuz83Ee2HIsvGuwi14w" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJHvD83Ee2HIsvGuwi14w" value="4"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="_BJJHvT83Ee2HIsvGuwi14w" name="mailingCampaign">
        <attribute defType="com.stambia.xml.element.originalType" id="_BJJHvj83Ee2HIsvGuwi14w" value="mailingCampaign"/>
        <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJHvz83Ee2HIsvGuwi14w" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJHwD83Ee2HIsvGuwi14w" value="1"/>
        <node defType="com.stambia.xml.sequence" id="_BJJHwT83Ee2HIsvGuwi14w">
          <attribute defType="com.stambia.xml.sequence.position" id="_BJJHwj83Ee2HIsvGuwi14w" value="0"/>
          <node defType="com.stambia.xml.element" id="_BJJHwz83Ee2HIsvGuwi14w" name="customer">
            <attribute defType="com.stambia.xml.element.originalType" id="_BJJHxD83Ee2HIsvGuwi14w" value="customer"/>
            <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJHxT83Ee2HIsvGuwi14w" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJHxj83Ee2HIsvGuwi14w" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="_BJJHxz83Ee2HIsvGuwi14w" name="lastName">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHyD83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHyT83Ee2HIsvGuwi14w" value="0"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHyj83Ee2HIsvGuwi14w" name="titleCode">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHyz83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHzD83Ee2HIsvGuwi14w" value="1"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJHzT83Ee2HIsvGuwi14w" name="title">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJHzj83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJHzz83Ee2HIsvGuwi14w" value="2"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJH0D83Ee2HIsvGuwi14w" name="customerId">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJH0T83Ee2HIsvGuwi14w" value="byte"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJH0j83Ee2HIsvGuwi14w" value="3"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJH0z83Ee2HIsvGuwi14w" name="company">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJH1D83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJH1T83Ee2HIsvGuwi14w" value="4"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJH1j83Ee2HIsvGuwi14w" name="birthDate">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJH1z83Ee2HIsvGuwi14w" value="date"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJH2D83Ee2HIsvGuwi14w" value="5"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_BJJH2T83Ee2HIsvGuwi14w" name="firstName">
              <attribute defType="com.stambia.xml.attribute.type" id="_BJJH2j83Ee2HIsvGuwi14w" value="string"/>
              <attribute defType="com.stambia.xml.attribute.position" id="_BJJH2z83Ee2HIsvGuwi14w" value="6"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="_BJJH3D83Ee2HIsvGuwi14w">
              <attribute defType="com.stambia.xml.sequence.position" id="_BJJH3T83Ee2HIsvGuwi14w" value="0"/>
              <node defType="com.stambia.xml.element" id="_BJJH3j83Ee2HIsvGuwi14w" name="email">
                <attribute defType="com.stambia.xml.element.originalType" id="_BJJH3z83Ee2HIsvGuwi14w" value="email"/>
                <attribute defType="com.stambia.xml.element.minOccurs" id="_BJJH4D83Ee2HIsvGuwi14w" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="_BJJH4T83Ee2HIsvGuwi14w" value="-1"/>
                <node defType="com.stambia.xml.attribute" id="_BJJH4j83Ee2HIsvGuwi14w" name="mailingAllowed">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJH4z83Ee2HIsvGuwi14w" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJH5D83Ee2HIsvGuwi14w" value="0"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJH5T83Ee2HIsvGuwi14w" name="emailType">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJH5j83Ee2HIsvGuwi14w" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJH5z83Ee2HIsvGuwi14w" value="1"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJH6D83Ee2HIsvGuwi14w" name="emailId">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJH6T83Ee2HIsvGuwi14w" value="byte"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJH6j83Ee2HIsvGuwi14w" value="2"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="_BJJH6z83Ee2HIsvGuwi14w" name="emailAddress">
                  <attribute defType="com.stambia.xml.attribute.type" id="_BJJH7D83Ee2HIsvGuwi14w" value="string"/>
                  <attribute defType="com.stambia.xml.attribute.position" id="_BJJH7T83Ee2HIsvGuwi14w" value="3"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.xml.namespace" id="_BJJH7j83Ee2HIsvGuwi14w" name="http://stambia.org/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_BJJH7z83Ee2HIsvGuwi14w" value="mgt"/>
  </node>
</md:node>