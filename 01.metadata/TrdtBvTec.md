<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.schema" id="_RocwgICYEemlY6iTndw9vg" name="BV_TEC" md:ref="../../serverConfigurations/teradataDwh1.md#_6M8VcBx_EeiIkZ0m_Wy3GA?fileId=_QNnCQDY8Eeevy5wHJGzQUA$type=md$name=BV_TEC?">
  <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_RodXkICYEemlY6iTndw9vg" value=""/>
  <node defType="com.stambia.rdbms.datastore" id="_RodXkYCYEemlY6iTndw9vg" name="TKGEN_HBASE_LINEAGE">
    <attribute defType="com.stambia.rdbms.datastore.name" id="_RodXkoCYEemlY6iTndw9vg" value="TKGEN_HBASE_LINEAGE"/>
    <attribute defType="com.stambia.rdbms.datastore.type" id="_RodXk4CYEemlY6iTndw9vg" value="TABLE"/>
    <node defType="com.stambia.rdbms.primaryindex" id="_RodXlICYEemlY6iTndw9vg" name="PrimaryIndex">
      <attribute defType="com.stambia.rdbms.primaryindex.uniqueIndex" id="_RodXlYCYEemlY6iTndw9vg" value="true"/>
      <node defType="com.stambia.rdbms.colref" id="_RodXloCYEemlY6iTndw9vg" name="ROWKEY">
        <attribute defType="com.stambia.rdbms.colref.ref" id="_Rod-oICYEemlY6iTndw9vg" ref="#_Rod-oYCYEemlY6iTndw9vg?fileId=_RocwgICYEemlY6iTndw9vg$type=md$name=ROWKEY?"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Rod-oYCYEemlY6iTndw9vg" name="ROWKEY" position="1">
      <attribute defType="com.stambia.rdbms.column.type" id="_Rod-ooCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Rod-o4CYEemlY6iTndw9vg" value="ROWKEY"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Rod-pICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Rod-pYCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Rod-poCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Rod-p4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Rod-qICYEemlY6iTndw9vg" value="100"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Rod-qYCYEemlY6iTndw9vg" name="ENV" position="2">
      <attribute defType="com.stambia.rdbms.column.type" id="_Rod-qoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Rod-q4CYEemlY6iTndw9vg" value="ENV"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Rod-rICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Rod-rYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Rod-roCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Rod-r4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Rod-sICYEemlY6iTndw9vg" value="5"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Rod-sYCYEemlY6iTndw9vg" name="BU" position="3">
      <attribute defType="com.stambia.rdbms.column.type" id="_Rod-soCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Rod-s4CYEemlY6iTndw9vg" value="BU"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Rod-tICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Rod-tYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Rod-toCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Rod-t4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Rod-uICYEemlY6iTndw9vg" value="3"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Rod-uYCYEemlY6iTndw9vg" name="GLOBAL_ENTITY" position="5">
      <attribute defType="com.stambia.rdbms.column.type" id="_Rod-uoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Rod-u4CYEemlY6iTndw9vg" value="GLOBAL_ENTITY"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RoelsICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RoelsYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RoelsoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roels4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RoeltICYEemlY6iTndw9vg" value="50"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RoeltYCYEemlY6iTndw9vg" name="FILENAME" position="6">
      <attribute defType="com.stambia.rdbms.column.type" id="_RoeltoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roelt4CYEemlY6iTndw9vg" value="FILENAME"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RoeluICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RoeluYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RoeluoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roelu4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RoelvICYEemlY6iTndw9vg" value="250"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RoelvYCYEemlY6iTndw9vg" name="FILESIZE" position="7">
      <attribute defType="com.stambia.rdbms.column.type" id="_RoelvoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roelv4CYEemlY6iTndw9vg" value="FILESIZE"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RoelwICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RoelwYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RoelwoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roelw4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RoelxICYEemlY6iTndw9vg" value="250"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RoelxYCYEemlY6iTndw9vg" name="LINEAGE_KEY" position="8">
      <attribute defType="com.stambia.rdbms.column.type" id="_RoelxoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roelx4CYEemlY6iTndw9vg" value="LINEAGE_KEY"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RoelyICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RoelyYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RoelyoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roely4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RoelzICYEemlY6iTndw9vg" value="250"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RoelzYCYEemlY6iTndw9vg" name="SEQUENCE_NUMBER" position="9">
      <attribute defType="com.stambia.rdbms.column.type" id="_RoelzoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roelz4CYEemlY6iTndw9vg" value="SEQUENCE_NUMBER"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Roel0ICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Roel0YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Roel0oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roel04CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Roel1ICYEemlY6iTndw9vg" value="10"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Roel1YCYEemlY6iTndw9vg" name="STEP" position="10">
      <attribute defType="com.stambia.rdbms.column.type" id="_Roel1oCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roel14CYEemlY6iTndw9vg" value="STEP"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Roel2ICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Roel2YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Roel2oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roel24CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Roel3ICYEemlY6iTndw9vg" value="50"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Roel3YCYEemlY6iTndw9vg" name="STEP_START" position="11">
      <attribute defType="com.stambia.rdbms.column.type" id="_Roel3oCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roel34CYEemlY6iTndw9vg" value="STEP_START"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Roel4ICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Roel4YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Roel4oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roel44CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Roel5ICYEemlY6iTndw9vg" value="50"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Roel5YCYEemlY6iTndw9vg" name="STEP_END" position="12">
      <attribute defType="com.stambia.rdbms.column.type" id="_Roel5oCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roel54CYEemlY6iTndw9vg" value="STEP_END"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_Roel6ICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_Roel6YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_Roel6oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_Roel64CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_Roel7ICYEemlY6iTndw9vg" value="50"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_Roel7YCYEemlY6iTndw9vg" name="STEP_STATUS" position="13">
      <attribute defType="com.stambia.rdbms.column.type" id="_Roel7oCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_Roel74CYEemlY6iTndw9vg" value="STEP_STATUS"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RofMwICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RofMwYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RofMwoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_RofMw4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RofMxICYEemlY6iTndw9vg" value="50"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RofMxYCYEemlY6iTndw9vg" name="STEP_MESSAGE" position="14">
      <attribute defType="com.stambia.rdbms.column.type" id="_RofMxoCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_RofMx4CYEemlY6iTndw9vg" value="STEP_MESSAGE"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RofMyICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RofMyYCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RofMyoCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_RofMy4CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RofMzICYEemlY6iTndw9vg" value="250"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RofMzYCYEemlY6iTndw9vg" name="RECORD_COUNT" position="15">
      <attribute defType="com.stambia.rdbms.column.type" id="_RofMzoCYEemlY6iTndw9vg" value="DECIMAL"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_RofMz4CYEemlY6iTndw9vg" value="RECORD_COUNT"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RofM0ICYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RofM0YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RofM0oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_RofM04CYEemlY6iTndw9vg" value=""/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RofM1ICYEemlY6iTndw9vg" value="15"/>
    </node>
    <node defType="com.stambia.rdbms.column" id="_RofM1YCYEemlY6iTndw9vg" name="PILAR" position="4">
      <attribute defType="com.stambia.rdbms.column.type" id="_RofM1oCYEemlY6iTndw9vg" value="VARCHAR"/>
      <attribute defType="com.stambia.rdbms.column.name" id="_RofM14CYEemlY6iTndw9vg" value="PILAR"/>
      <attribute defType="com.stambia.rdbms.column.charset" id="_RofM2ICYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.nullable" id="_RofM2YCYEemlY6iTndw9vg" value="1"/>
      <attribute defType="com.stambia.rdbms.column.digits" id="_RofM2oCYEemlY6iTndw9vg" value="0"/>
      <attribute defType="com.stambia.rdbms.column.upperCase" id="_RofM24CYEemlY6iTndw9vg" value="N"/>
      <attribute defType="com.stambia.rdbms.column.size" id="_RofM3ICYEemlY6iTndw9vg" value="50"/>
    </node>
  </node>
</md:node>