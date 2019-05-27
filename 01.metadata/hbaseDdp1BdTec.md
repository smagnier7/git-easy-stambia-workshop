<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.hbase.namespace" id="_RofM3YCYEemlY6iTndw9vg" name="BD_TEC" md:ref="../../serverConfigurations/hbaseDdp1.md#_iEONcDMyEeixm78zJKlxIg?fileId=_oFr1UAHJEeic5bHKfjS8DA$type=md$name=BD_TEC?">
  <attribute defType="com.stambia.hbase.namespace.reverseTableFilter" id="_Rofz0ICYEemlY6iTndw9vg" value="TFGEN_TEC_LINEAGE%"/>
  <node defType="com.stambia.hbase.datastore" id="_Rofz0YCYEemlY6iTndw9vg" name="TFGEN_TEC_LINEAGE">
    <attribute defType="com.stambia.hbase.datastore.physicalName" id="_Rofz0oCYEemlY6iTndw9vg" value="TFGEN_TEC_LINEAGE"/>
    <node defType="com.stambia.hbase.column" id="_Rofz04CYEemlY6iTndw9vg" name="row_key" position="1">
      <attribute defType="com.stambia.hbase.column.isRowKey" id="_Rofz1ICYEemlY6iTndw9vg" value="true"/>
      <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz1YCYEemlY6iTndw9vg" value="row_key"/>
    </node>
    <node defType="com.stambia.hbase.family" id="_Rofz1oCYEemlY6iTndw9vg" name="f1" position="1">
      <attribute defType="com.stambia.hbase.family.physicalName" id="_Rofz14CYEemlY6iTndw9vg" value="f1"/>
      <node defType="com.stambia.hbase.column" id="_Rofz2ICYEemlY6iTndw9vg" name="ENV" position="1">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz2YCYEemlY6iTndw9vg" value="ENV"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz2oCYEemlY6iTndw9vg" name="buNumber" position="2">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz24CYEemlY6iTndw9vg" value="buNumber"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz3ICYEemlY6iTndw9vg" name="dataFormat" position="3">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz3YCYEemlY6iTndw9vg" value="dataFormat"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz3oCYEemlY6iTndw9vg" name="entryDate" position="4">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz34CYEemlY6iTndw9vg" value="entryDate"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz4ICYEemlY6iTndw9vg" name="fileSize" position="5">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz4YCYEemlY6iTndw9vg" value="fileSize"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz4oCYEemlY6iTndw9vg" name="lineageStartDate" position="6">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz44CYEemlY6iTndw9vg" value="lineageStartDate"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz5ICYEemlY6iTndw9vg" name="timeLog" position="7">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz5YCYEemlY6iTndw9vg" value="timeLog"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz5oCYEemlY6iTndw9vg" name="entity" position="8">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz54CYEemlY6iTndw9vg" value="entity"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz6ICYEemlY6iTndw9vg" name="extractionDate" position="9">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz6YCYEemlY6iTndw9vg" value="extractionDate"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz6oCYEemlY6iTndw9vg" name="filename" position="10">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz64CYEemlY6iTndw9vg" value="filename"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz7ICYEemlY6iTndw9vg" name="flowStartTS" position="11">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz7YCYEemlY6iTndw9vg" value="flowStartTS"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz7oCYEemlY6iTndw9vg" name="globalEntity" position="12">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz74CYEemlY6iTndw9vg" value="globalEntity"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz8ICYEemlY6iTndw9vg" name="initialFilename" position="13">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz8YCYEemlY6iTndw9vg" value="initialFilename"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz8oCYEemlY6iTndw9vg" name="lineageKey" position="14">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz84CYEemlY6iTndw9vg" value="lineageKey"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz9ICYEemlY6iTndw9vg" name="pillar" position="15">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz9YCYEemlY6iTndw9vg" value="pillar"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz9oCYEemlY6iTndw9vg" name="prm" position="16">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz94CYEemlY6iTndw9vg" value="prm"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz-ICYEemlY6iTndw9vg" name="sequenceNumber" position="17">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz-YCYEemlY6iTndw9vg" value="sequenceNumber"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz-oCYEemlY6iTndw9vg" name="step" position="18">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz-4CYEemlY6iTndw9vg" value="step"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Rofz_ICYEemlY6iTndw9vg" name="stepEndTS" position="19">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Rofz_YCYEemlY6iTndw9vg" value="stepEndTS"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga4ICYEemlY6iTndw9vg" name="stepStartTS" position="20">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga4YCYEemlY6iTndw9vg" value="stepStartTS"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga4oCYEemlY6iTndw9vg" name="stepStatus" position="21">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga44CYEemlY6iTndw9vg" value="stepStatus"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga5ICYEemlY6iTndw9vg" name="uuid" position="22">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga5YCYEemlY6iTndw9vg" value="uuid"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga5oCYEemlY6iTndw9vg" name="prmBu" position="23">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga54CYEemlY6iTndw9vg" value="prmBu"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga6ICYEemlY6iTndw9vg" name="stepMessage" position="24">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga6YCYEemlY6iTndw9vg" value="stepMessage"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga6oCYEemlY6iTndw9vg" name="record_count" position="25">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga64CYEemlY6iTndw9vg" value="record_count"/>
      </node>
      <node defType="com.stambia.hbase.column" id="_Roga7ICYEemlY6iTndw9vg" name="_0" position="26">
        <attribute defType="com.stambia.hbase.column.physicalName" id="_Roga7YCYEemlY6iTndw9vg" value="_0"/>
      </node>
    </node>
  </node>
</md:node>