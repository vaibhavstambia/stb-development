<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_1W9DcAxeEeu8CJE7Ik3tcg" md:ref="platform:/plugin/com.indy.environment/technology/file/standard.file.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_1k3joAxeEeu8CJE7Ik3tcg" name="folder">
    <attribute defType="com.stambia.file.directory.path" id="_1lM60AxeEeu8CJE7Ik3tcg" value="${/CORE_TEMPORARY_FOLDER}$"/>
    <node defType="com.stambia.file.file" id="_BgJC0QxfEeu8CJE7Ik3tcg" name="ws_output">
      <attribute defType="com.stambia.file.file.physicalName" id="_FnJ7gAxfEeu8CJE7Ik3tcg" value="ws_output.csv"/>
      <attribute defType="com.stambia.file.file.type" id="_HAKV0AxfEeu8CJE7Ik3tcg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_7QDWEAxkEeu8CJE7Ik3tcg" value="0"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_7o7JEAxkEeu8CJE7Ik3tcg"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_7o7wIAxkEeu8CJE7Ik3tcg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_7o7wIQxkEeu8CJE7Ik3tcg" value="2C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_7o7wIgxkEeu8CJE7Ik3tcg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_7o8XMAxkEeu8CJE7Ik3tcg" value="2E"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_7o8-QAxkEeu8CJE7Ik3tcg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_7o-MYAxkEeu8CJE7Ik3tcg" value="0"/>
    </node>
    <node defType="com.stambia.file.file" id="_9gPBOw0uEeu8CJE7Ik3tcg" name="ws_customer">
      <attribute defType="com.stambia.file.file.physicalName" id="_9gPoQA0uEeu8CJE7Ik3tcg" value="customer.txt"/>
      <attribute defType="com.stambia.file.file.type" id="_9gPoQQ0uEeu8CJE7Ik3tcg" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_9gPoQg0uEeu8CJE7Ik3tcg" value="0"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_9gPoQw0uEeu8CJE7Ik3tcg"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_9gPoRA0uEeu8CJE7Ik3tcg" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_9gPoRQ0uEeu8CJE7Ik3tcg" value="2C"/>
      <attribute defType="com.stambia.file.file.stringDelimiter" id="_9gPoRg0uEeu8CJE7Ik3tcg"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_9gPoRw0uEeu8CJE7Ik3tcg" value="2E"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_9gPoSA0uEeu8CJE7Ik3tcg" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_9gPoSQ0uEeu8CJE7Ik3tcg" value="1"/>
      <node defType="com.stambia.file.field" id="_DhAQ0A0vEeu8CJE7Ik3tcg" name="cust_name" position="1">
        <attribute defType="com.stambia.file.field.physicalName" id="_DhCGAA0vEeu8CJE7Ik3tcg" value="C1"/>
        <attribute defType="com.stambia.file.field.type" id="_DhCGAQ0vEeu8CJE7Ik3tcg" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="_DhCGAg0vEeu8CJE7Ik3tcg" value="50"/>
      </node>
    </node>
  </node>
</md:node>