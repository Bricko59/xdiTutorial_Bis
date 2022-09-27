<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.function.folder" id="_fp4D0D5kEe2HIsvGuwi14w" md:ref="resource.md#UUID_MD_UDF?fileId=UUID_MD_UDF$type=md$name=User%20Defined%20Functions?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.function.folder.prefix" id="_r8EOMD5kEe2HIsvGuwi14w" value="tr"/>
  <node defType="com.stambia.function.function" id="_r8DnIT5kEe2HIsvGuwi14w" name="concat3">
    <node defType="com.stambia.function.parameter" id="_r8DnIj5kEe2HIsvGuwi14w" name="str1" position="1"/>
    <node defType="com.stambia.function.parameter" id="_r8DnIz5kEe2HIsvGuwi14w" name="str2" position="2"/>
    <node defType="com.stambia.function.parameter" id="_r8DnJD5kEe2HIsvGuwi14w" name="str3" position="3"/>
    <node defType="com.stambia.function.implementation" id="_tEwUkT5kEe2HIsvGuwi14w" name="pipe_pipe">
      <attribute defType="com.stambia.function.implementation.expression" id="_3jBqQD5kEe2HIsvGuwi14w" value="concat($str1,$str2,$str3)"/>
      <attribute defType="com.stambia.function.implementation.productCode" id="_54o2wD5kEe2HIsvGuwi14w">
        <values>HYPERSONIC_SQL</values>
      </attribute>
    </node>
  </node>
  <node defType="com.stambia.function.function" id="_r8DnJT5kEe2HIsvGuwi14w" name="removeSpace">
    <node defType="com.stambia.function.parameter" id="_r8DnJj5kEe2HIsvGuwi14w" name="str" position="1"/>
    <node defType="com.stambia.function.implementation" id="_EFwLAT5lEe2HIsvGuwi14w" name="trim">
      <attribute defType="com.stambia.function.implementation.productCode" id="_GmqokD5lEe2HIsvGuwi14w">
        <values>HYPERSONIC_SQL</values>
      </attribute>
      <attribute defType="com.stambia.function.implementation.expression" id="_IBscID5lEe2HIsvGuwi14w" value="trim($str)"/>
    </node>
  </node>
  <node defType="com.stambia.function.function" id="_r8DnJz5kEe2HIsvGuwi14w" name="upperCase">
    <node defType="com.stambia.function.parameter" id="_r8DnKD5kEe2HIsvGuwi14w" name="str" position="1"/>
    <node defType="com.stambia.function.implementation" id="_LI3ocT5lEe2HIsvGuwi14w" name="upper">
      <attribute defType="com.stambia.function.implementation.productCode" id="_Nb-6kD5lEe2HIsvGuwi14w">
        <values>HYPERSONIC_SQL</values>
      </attribute>
      <attribute defType="com.stambia.function.implementation.expression" id="_QD1GkD5lEe2HIsvGuwi14w" value="upper($str)"/>
    </node>
  </node>
  <node defType="com.stambia.function.function" id="_r8DnKT5kEe2HIsvGuwi14w" name="currentTimestamp">
    <node defType="com.stambia.function.implementation" id="_-t-1ET5kEe2HIsvGuwi14w" name="current_timestamp">
      <attribute defType="com.stambia.function.implementation.productCode" id="_BveQID5lEe2HIsvGuwi14w">
        <values>HYPERSONIC_SQL</values>
      </attribute>
      <attribute defType="com.stambia.function.implementation.expression" id="_C2KycD5lEe2HIsvGuwi14w" value="current_timestamp"/>
    </node>
  </node>
</md:node>