<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.wsdl.wsdl" id="_RjSaIEAFEe2tTJjc7xXTDQ" name="geocoder" md:ref="resource.tech#UUID_TECH_WSDL1?fileId=UUID_TECH_WSDL1$type=tech$name=wsdl?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.wsdl.wsdl.xsdReverseVersion" id="_RjXSoEAFEe2tTJjc7xXTDQ" value="1"/>
  <attribute defType="com.stambia.wsdl.wsdl.url" id="_Rp0f8EAFEe2tTJjc7xXTDQ" value="http://geocoder.stambia.org:62220/geocoder?wsdl"/>
  <attribute defType="com.stambia.wsdl.wsdl.prefixForElement" id="_YVVVsEAFEe2tTJjc7xXTDQ" value="unqualified"/>
  <attribute defType="com.stambia.wsdl.wsdl.prefixForAttribute" id="_YVVVsUAFEe2tTJjc7xXTDQ" value="unqualified"/>
  <attribute defType="com.stambia.wsdl.wsdl.targetNamespace" id="_YVVVskAFEe2tTJjc7xXTDQ" value="http://ws.tutorial.demo.indy.com/"/>
  <node defType="com.stambia.xml.namespace" id="_YVS5d0AFEe2tTJjc7xXTDQ" name="http://schemas.xmlsoap.org/wsdl/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5eEAFEe2tTJjc7xXTDQ" value="ns"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5eUAFEe2tTJjc7xXTDQ" name="http://www.w3.org/ns/ws-policy">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5ekAFEe2tTJjc7xXTDQ" value="wsp"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5e0AFEe2tTJjc7xXTDQ" name="http://ws.tutorial.demo.indy.com/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5fEAFEe2tTJjc7xXTDQ" value="tns"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5fUAFEe2tTJjc7xXTDQ" name="http://schemas.xmlsoap.org/ws/2004/09/policy">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5fkAFEe2tTJjc7xXTDQ" value="wsp1_2"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5f0AFEe2tTJjc7xXTDQ" name="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5gEAFEe2tTJjc7xXTDQ" value="wsu"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5gUAFEe2tTJjc7xXTDQ" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5gkAFEe2tTJjc7xXTDQ" value="xsd"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5g0AFEe2tTJjc7xXTDQ" name="http://schemas.xmlsoap.org/wsdl/soap/">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5hEAFEe2tTJjc7xXTDQ" value="soap"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_YVS5hUAFEe2tTJjc7xXTDQ" name="http://www.w3.org/2007/05/addressing/metadata">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_YVS5hkAFEe2tTJjc7xXTDQ" value="wsam"/>
  </node>
  <node defType="com.stambia.wsdl.service" id="_YVS5h0AFEe2tTJjc7xXTDQ" name="GeoCode_Service">
    <node defType="com.stambia.wsdl.port" id="_YVS5iEAFEe2tTJjc7xXTDQ" name="GeoCode_Port">
      <attribute defType="com.stambia.wsdl.port.address" id="_YVS5iUAFEe2tTJjc7xXTDQ" value="http://geocoder.stambia.org:62220/geocoder"/>
      <attribute defType="com.stambia.wsdl.port.protocol" id="_YVS5ikAFEe2tTJjc7xXTDQ" value="SOAP"/>
      <attribute defType="com.stambia.wsdl.port.transportURI" id="_YVS5i0AFEe2tTJjc7xXTDQ" value="http://schemas.xmlsoap.org/soap/http"/>
      <attribute defType="com.stambia.wsdl.port.style" id="_YVS5jEAFEe2tTJjc7xXTDQ" value="document"/>
      <node defType="com.stambia.wsdl.operation" id="_YVS5jUAFEe2tTJjc7xXTDQ" name="geocode_address">
        <node defType="com.stambia.wsdl.input" id="_YVS5kEAFEe2tTJjc7xXTDQ">
          <node defType="com.stambia.wsdl.part" id="_YVS5kUAFEe2tTJjc7xXTDQ" name="parameters">
            <attribute defType="com.stambia.wsdl.part.bindingType" id="_YVS5kkAFEe2tTJjc7xXTDQ" value="soap:body"/>
            <attribute defType="com.stambia.wsdl.part.use" id="_YVS5lEAFEe2tTJjc7xXTDQ" value="literal"/>
            <node defType="com.stambia.xml.element" id="_YVS5lUAFEe2tTJjc7xXTDQ" name="geocode_address" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_YVS5lkAFEe2tTJjc7xXTDQ" value="tns:geocode_address"/>
              <node defType="com.stambia.xml.sequence" id="_YVS5l0AFEe2tTJjc7xXTDQ" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_YVS5mEAFEe2tTJjc7xXTDQ" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_YVS5mUAFEe2tTJjc7xXTDQ" value="1"/>
                <node defType="com.stambia.xml.element" id="_YVS5mkAFEe2tTJjc7xXTDQ" name="address" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5m0AFEe2tTJjc7xXTDQ" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5nEAFEe2tTJjc7xXTDQ" value="1"/>
                  <attribute defType="com.stambia.xml.element.type" id="_YVS5nUAFEe2tTJjc7xXTDQ" value="string"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_YVS5nkAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.output" id="_YVS5n0AFEe2tTJjc7xXTDQ">
          <node defType="com.stambia.wsdl.part" id="_YVS5oEAFEe2tTJjc7xXTDQ" name="parameters">
            <attribute defType="com.stambia.wsdl.part.bindingType" id="_YVS5oUAFEe2tTJjc7xXTDQ" value="soap:body"/>
            <attribute defType="com.stambia.wsdl.part.use" id="_YVS5o0AFEe2tTJjc7xXTDQ" value="literal"/>
            <node defType="com.stambia.xml.element" id="_YVS5pEAFEe2tTJjc7xXTDQ" name="geocode_addressResponse" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_YVS5pUAFEe2tTJjc7xXTDQ" value="tns:geocode_addressResponse"/>
              <node defType="com.stambia.xml.sequence" id="_YVS5pkAFEe2tTJjc7xXTDQ" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_YVS5p0AFEe2tTJjc7xXTDQ" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_YVS5qEAFEe2tTJjc7xXTDQ" value="1"/>
                <node defType="com.stambia.xml.element" id="_YVS5qUAFEe2tTJjc7xXTDQ" name="return" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5qkAFEe2tTJjc7xXTDQ" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5q0AFEe2tTJjc7xXTDQ" value="1"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_YVS5rEAFEe2tTJjc7xXTDQ" value="tns:localisation"/>
                  <node defType="com.stambia.xml.sequence" id="_YVS5rUAFEe2tTJjc7xXTDQ" position="3">
                    <attribute defType="com.stambia.xml.sequence.minOccurs" id="_YVS5rkAFEe2tTJjc7xXTDQ" value="1"/>
                    <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_YVS5r0AFEe2tTJjc7xXTDQ" value="1"/>
                    <node defType="com.stambia.xml.element" id="_YVS5sEAFEe2tTJjc7xXTDQ" name="city" position="0">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5sUAFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5skAFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5s0AFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5tEAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5tUAFEe2tTJjc7xXTDQ" name="latitude" position="1">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5tkAFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5t0AFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5uEAFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5uUAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5ukAFEe2tTJjc7xXTDQ" name="longitude" position="2">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5u0AFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5vEAFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5vUAFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5vkAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5v0AFEe2tTJjc7xXTDQ" name="number" position="3">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5wEAFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5wUAFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5wkAFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5w0AFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5xEAFEe2tTJjc7xXTDQ" name="state" position="4">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5xUAFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5xkAFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5x0AFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5yEAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5yUAFEe2tTJjc7xXTDQ" name="street" position="5">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5ykAFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS5y0AFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS5zEAFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS5zUAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                    <node defType="com.stambia.xml.element" id="_YVS5zkAFEe2tTJjc7xXTDQ" name="zip" position="6">
                      <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS5z0AFEe2tTJjc7xXTDQ" value="0"/>
                      <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS50EAFEe2tTJjc7xXTDQ" value="1"/>
                      <attribute defType="com.stambia.xml.element.type" id="_YVS50UAFEe2tTJjc7xXTDQ" value="string"/>
                      <attribute defType="com.stambia.xml.element.originalType" id="_YVS50kAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                    </node>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.fault" id="_YVS500AFEe2tTJjc7xXTDQ" name="Exception">
          <node defType="com.stambia.wsdl.part" id="_YVS51EAFEe2tTJjc7xXTDQ" name="fault">
            <node defType="com.stambia.xml.element" id="_YVS51UAFEe2tTJjc7xXTDQ" name="Exception" position="0">
              <attribute defType="com.stambia.xml.element.originalType" id="_YVS51kAFEe2tTJjc7xXTDQ" value="tns:Exception"/>
              <node defType="com.stambia.xml.sequence" id="_YVS510AFEe2tTJjc7xXTDQ" position="3">
                <attribute defType="com.stambia.xml.sequence.minOccurs" id="_YVS52EAFEe2tTJjc7xXTDQ" value="1"/>
                <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_YVS52UAFEe2tTJjc7xXTDQ" value="1"/>
                <node defType="com.stambia.xml.element" id="_YVS52kAFEe2tTJjc7xXTDQ" name="message" position="0">
                  <attribute defType="com.stambia.xml.element.minOccurs" id="_YVS520AFEe2tTJjc7xXTDQ" value="0"/>
                  <attribute defType="com.stambia.xml.element.maxOccurs" id="_YVS53EAFEe2tTJjc7xXTDQ" value="1"/>
                  <attribute defType="com.stambia.xml.element.type" id="_YVS53UAFEe2tTJjc7xXTDQ" value="string"/>
                  <attribute defType="com.stambia.xml.element.originalType" id="_YVS53kAFEe2tTJjc7xXTDQ" value="xsd:string"/>
                </node>
              </node>
            </node>
          </node>
        </node>
        <node defType="com.stambia.wsdl.fault" id="_YVS530AFEe2tTJjc7xXTDQ" name="StandardFault">
          <node defType="com.stambia.wsdl.part" id="_YVS54EAFEe2tTJjc7xXTDQ" name="fault">
            <node defType="com.stambia.xml.element" id="_YVS54UAFEe2tTJjc7xXTDQ" name="faultcode">
              <attribute defType="com.stambia.xml.element.type" id="_YVS54kAFEe2tTJjc7xXTDQ" value="string"/>
            </node>
            <node defType="com.stambia.xml.element" id="_YVS540AFEe2tTJjc7xXTDQ" name="faultstring">
              <attribute defType="com.stambia.xml.element.type" id="_YVS55EAFEe2tTJjc7xXTDQ" value="string"/>
            </node>
            <node defType="com.stambia.xml.element" id="_YVS55UAFEe2tTJjc7xXTDQ" name="faultactor">
              <attribute defType="com.stambia.xml.element.type" id="_YVS55kAFEe2tTJjc7xXTDQ" value="string"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>