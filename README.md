![900_Towseef-Dar_Reno2_1638183427 6789](https://github.com/user-attachments/assets/436f78aa-1427-4c2b-86c1-5171825f6812)
# Washoe Tourism Impact

- Darryn Johnson
- link to repository : [washoe_tourism_impact](https://github.com/Djohnson1313/washoe_tourism_impact)
- link to notebook : [washoe_tourism_impact_nb.ipynb](https://github.com/Djohnson1313/washoe_tourism_impact/blob/main/washoe_tourism_impact_nb.ipynb)
- original dataset : [nevadatomorrow.org](https://www.nevadatomorrow.org/indicators/index/view?indicatorId=14201&localeId=1813)
- header image : [pictorem.com](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pictorem.com%2F484717%2Freno-nevada-skyline-bw%2F%3Fsrsltid%3DAfmBOoqtTx36--3wEmi0s96CEkAgzApqe98EEJmEbPovmwUDqvHcZnw0&psig=AOvVaw05D7O5Dh0QmcN-A6yqkS0V&ust=1751490924828000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMDP8a7KnI4DFQAAAAAdAAAAABAE)
- site used for visualizations in README.md : [Tableau](https://www.tableau.com/trial/tableau-software?d=7013y000002ExxqAAC&nc=7013y000002EykJAAS&utm_content=7013y000002ExxqAAC&utm_source=google&utm_medium=paid_search&utm_campaign=21198912846&utm_adgroup=159894453766&utm_term=tableau&utm_matchtype=p&gad_source=1&gad_campaignid=21198912846&gbraid=0AAAAADtjuu8BLu06nNeNQGgSAw0v5sRp8&gclid=Cj0KCQjwjo7DBhCrARIsACWauSkAv8Mvoj-JRbZw-AYcXgGTDVBrfJ9761AEZwIwuM7QJdJR-jXijogaArkoEALw_wcB&gclsrc=aw.ds)

# Business Understanding 
This repository and notebook intend to dive into the economics of the Washoe Valley area within Northern Nevada using data collected on tourism and the income it generates. This will primarily be done through breaking down how tourists spend their money by category, which include : `Food and Beverage`, `Gaming`, `Lodging`, `Recreation` and `Retail`. This information allows local businesses to target a specific demographic of tourists they belive they can best serve, therefore bringing more money and people into the economy of northern Nevada.

<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20252.25.0514.2217                               -->
<workbook original-version='18.1' source-build='2025.2.0 (20252.25.0514.2217)' source-platform='win' version='18.1' xml:base='https://public.tableau.com' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <AccessibleZoneTabOrder />
    <AnimationOnByDefault />
    <AutoCreateAndUpdateDSDPhoneLayouts />
    <MarkAnimation />
    <ObjectModelEncapsulateLegacy />
    <ObjectModelExtractV2 />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
    <SetMembershipControl />
    <SheetIdentifierTracking />
    <SortTagCleanup />
    <_.fcp.VConnDownstreamExtractsWithWarnings.true...VConnDownstreamExtractsWithWarnings />
    <WindowsPersistSimpleIdentifiers />
  </document-format-change-manifest>
  <repository-location id='CategorySpendingBreakdown' path='/workbooks' revision='1.0' />
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <datasources>
    <datasource caption='indicator_data_download_20250626' inline='true' name='federated.1p52r7z1tcber311vk12z17mlny8' version='18.1'>
      <connection class='federated'>
        <named-connections>
          <named-connection caption='indicator_data_download_20250626' name='textscan.1fe19gz0vvtdqy14kxkh50wvw0f6'>
            <connection class='textscan' cleaning='yes' compat='no' csvFile='C:\Users\darry\Downloads\indicator_data_download_20250626.csv' dataRefreshTime='' directory='C:/Users/darry/Downloads' filename='C:/Users/darry/AppData/Local/Temp/TableauTemp/1yvhjzz0b7kt701csafwg03moeho/indicator_data_download_20250626.csv.xlsx' interpretationMode='8' password='' server='' validate='no' workgroup-auth-mode='as-is' />
          </named-connection>
        </named-connections>
        <relation connection='textscan.1fe19gz0vvtdqy14kxkh50wvw0f6' name='indicator_data_download_20250626.csv' table='[C:\Users\darry\Downloads\indicator_data_download_20250626#csv]' type='table'>
          <columns character-set='UTF-8' gridOrigin='A1:AC26:no:A1:AC26:1' header='yes' locale='en_US' separator=','>
            <column datatype='string' name='Indicator Name' ordinal='0' />
            <column datatype='string' name='What Is This Indicator' ordinal='1' />
            <column datatype='string' name='Location Type' ordinal='2' />
            <column datatype='string' name='Location' ordinal='3' />
            <column datatype='real' name='Indicator Rate Value' ordinal='4' />
            <column datatype='string' name='Indicator Rate Value Units' ordinal='5' />
            <column datatype='string' name='Rate Lower Confidence Interval' ordinal='6' />
            <column datatype='string' name='Rate Upper Confidence Interval' ordinal='7' />
            <column datatype='string' name='Indicator Count Value' ordinal='8' />
            <column datatype='string' name='Indicator Count Value Units' ordinal='9' />
            <column datatype='string' name='Count Lower Confidence Interval' ordinal='10' />
            <column datatype='string' name='Count Upper Confidence Interval' ordinal='11' />
            <column datatype='string' name='Indicator Value Unstable' ordinal='12' />
            <column datatype='date' date-parse-format='yyyy' name='Period of Measure' ordinal='13' />
            <column datatype='string' name='Data Source' ordinal='14' />
            <column datatype='string' name='Technical Note' ordinal='15' />
            <column datatype='string' name='Breakout Title' ordinal='16' />
            <column datatype='string' name='Breakout Category' ordinal='17' />
            <column datatype='string' name='Breakout Subcategory' ordinal='18' />
            <column datatype='real' name='Breakout Rate Value' ordinal='19' />
            <column datatype='string' name='Breakout Rate Value Units' ordinal='20' />
            <column datatype='string' name='Breakout Rate Lower Confidence Interval' ordinal='21' />
            <column datatype='string' name='Breakout Rate Upper Confidence Interval' ordinal='22' />
            <column datatype='string' name='Breakout Count Value' ordinal='23' />
            <column datatype='string' name='Breakout Count Value Units' ordinal='24' />
            <column datatype='string' name='Breakout Count Lower Confidence Interval' ordinal='25' />
            <column datatype='string' name='Breakout Count Upper Confidence Interval' ordinal='26' />
            <column datatype='string' name='Breakout Unstable' ordinal='27' />
            <column datatype='string' name='Breakout Footer' ordinal='28' />
          </columns>
        </relation>
        <metadata-records>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='character-set'>&quot;UTF-8&quot;</attribute>
              <attribute datatype='string' name='collation'>&quot;en_US&quot;</attribute>
              <attribute datatype='string' name='field-delimiter'>&quot;,&quot;</attribute>
              <attribute datatype='string' name='gridOrigin'>&quot;A1:AC26:no:A1:AC26:1&quot;</attribute>
              <attribute datatype='string' name='header-row'>&quot;true&quot;</attribute>
              <attribute datatype='string' name='locale'>&quot;en_US&quot;</attribute>
              <attribute datatype='string' name='single-char'>&quot;&quot;</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Indicator Name]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Name</remote-alias>
            <ordinal>0</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>What Is This Indicator</remote-name>
            <remote-type>129</remote-type>
            <local-name>[What Is This Indicator]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>What Is This Indicator</remote-alias>
            <ordinal>1</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Location Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Location Type]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Location Type</remote-alias>
            <ordinal>2</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Location</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Location]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Location</remote-alias>
            <ordinal>3</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Rate Value</remote-name>
            <remote-type>5</remote-type>
            <local-name>[Indicator Rate Value]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Rate Value</remote-alias>
            <ordinal>4</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Rate Value Units</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Indicator Rate Value Units]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Rate Value Units</remote-alias>
            <ordinal>5</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Rate Lower Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Rate Lower Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Rate Lower Confidence Interval</remote-alias>
            <ordinal>6</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Rate Upper Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Rate Upper Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Rate Upper Confidence Interval</remote-alias>
            <ordinal>7</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Count Value</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Indicator Count Value]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Count Value</remote-alias>
            <ordinal>8</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Count Value Units</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Indicator Count Value Units]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Count Value Units</remote-alias>
            <ordinal>9</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Count Lower Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Count Lower Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Count Lower Confidence Interval</remote-alias>
            <ordinal>10</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Count Upper Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Count Upper Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Count Upper Confidence Interval</remote-alias>
            <ordinal>11</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Indicator Value Unstable</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Indicator Value Unstable]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Indicator Value Unstable</remote-alias>
            <ordinal>12</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Period of Measure</remote-name>
            <remote-type>7</remote-type>
            <local-name>[Period of Measure]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Period of Measure</remote-alias>
            <ordinal>13</ordinal>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Data Source</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Data Source]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Data Source</remote-alias>
            <ordinal>14</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Technical Note</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Technical Note]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Technical Note</remote-alias>
            <ordinal>15</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Title</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Title]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Title</remote-alias>
            <ordinal>16</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Category</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Category]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Category</remote-alias>
            <ordinal>17</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Subcategory</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Subcategory]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Subcategory</remote-alias>
            <ordinal>18</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Rate Value</remote-name>
            <remote-type>5</remote-type>
            <local-name>[Breakout Rate Value]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Rate Value</remote-alias>
            <ordinal>19</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Rate Value Units</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Rate Value Units]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Rate Value Units</remote-alias>
            <ordinal>20</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Rate Lower Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Rate Lower Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Rate Lower Confidence Interval</remote-alias>
            <ordinal>21</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Rate Upper Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Rate Upper Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Rate Upper Confidence Interval</remote-alias>
            <ordinal>22</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Count Value</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Count Value]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Count Value</remote-alias>
            <ordinal>23</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Count Value Units</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Count Value Units]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Count Value Units</remote-alias>
            <ordinal>24</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Count Lower Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Count Lower Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Count Lower Confidence Interval</remote-alias>
            <ordinal>25</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Count Upper Confidence Interval</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Count Upper Confidence Interval]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Count Upper Confidence Interval</remote-alias>
            <ordinal>26</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Unstable</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Unstable]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Unstable</remote-alias>
            <ordinal>27</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Breakout Footer</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Breakout Footer]</local-name>
            <parent-name>[indicator_data_download_20250626.csv]</parent-name>
            <remote-alias>Breakout Footer</remote-alias>
            <ordinal>28</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <approx-count>1</approx-count>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
          </metadata-record>
        </metadata-records>
      </connection>
      <aliases enabled='yes' />
      <column datatype='string' hidden='true' name='[Breakout Count Lower Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Count Upper Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Count Value Units]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Count Value]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Footer]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Rate Lower Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Breakout Rate Upper Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Count Lower Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Count Upper Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Indicator Count Value Units]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Indicator Count Value]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Rate Lower Confidence Interval]' role='dimension' type='nominal' />
      <column datatype='string' hidden='true' name='[Rate Upper Confidence Interval]' role='dimension' type='nominal' />
      <column caption='indicator_data_download_20250626.csv' datatype='table' name='[__tableau_internal_object_id__].[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]' role='measure' type='quantitative' />
      <drill-paths>
        <drill-path name='Breakout Category, Breakout Subcategory'>
          <field>[Breakout Category]</field>
          <field>[Breakout Subcategory]</field>
        </drill-path>
        <drill-path name='Location, Location Type'>
          <field>[Location]</field>
          <field>[Location Type]</field>
        </drill-path>
      </drill-paths>
      <extract _.fcp.VConnDownstreamExtractsWithWarnings.true...user-specific='false' count='-1' enabled='true' object-id='' units='records'>
        <connection access_mode='readonly' author-locale='en_US' class='hyper' dbname='C:/Users/darry/AppData/Local/Temp/TableauTemp/#TableauTemp_0flyslg09kutog14xmzpr0hb4vky.hyper' default-settings='hyper' schema='Extract' sslmode='' tablename='Extract' update-time='07/01/2025 08:33:05 PM' username='tableau_internal_user'>
          <relation name='Extract' table='[Extract].[Extract]' type='table' />
          <metadata-records>
            <metadata-record class='column'>
              <remote-name>Indicator Name</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Indicator Name]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Indicator Name</remote-alias>
              <ordinal>0</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>What Is This Indicator</remote-name>
              <remote-type>129</remote-type>
              <local-name>[What Is This Indicator]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>What Is This Indicator</remote-alias>
              <ordinal>1</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Location Type</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Location Type]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Location Type</remote-alias>
              <ordinal>2</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Location</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Location]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Location</remote-alias>
              <ordinal>3</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Indicator Rate Value</remote-name>
              <remote-type>5</remote-type>
              <local-name>[Indicator Rate Value]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Indicator Rate Value</remote-alias>
              <ordinal>4</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>real</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>10</approx-count>
              <contains-null>true</contains-null>
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Indicator Rate Value Units</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Indicator Rate Value Units]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Indicator Rate Value Units</remote-alias>
              <ordinal>5</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Indicator Value Unstable</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Indicator Value Unstable]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Indicator Value Unstable</remote-alias>
              <ordinal>6</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Period of Measure</remote-name>
              <remote-type>133</remote-type>
              <local-name>[Period of Measure]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Period of Measure</remote-alias>
              <ordinal>7</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>date</local-type>
              <aggregation>Year</aggregation>
              <approx-count>10</approx-count>
              <contains-null>true</contains-null>
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Data Source</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Data Source]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Data Source</remote-alias>
              <ordinal>8</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Technical Note</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Technical Note]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Technical Note</remote-alias>
              <ordinal>9</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>1</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Title</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Breakout Title]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Title</remote-alias>
              <ordinal>10</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Category</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Breakout Category]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Category</remote-alias>
              <ordinal>11</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Subcategory</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Breakout Subcategory]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Subcategory</remote-alias>
              <ordinal>12</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>7</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Rate Value</remote-name>
              <remote-type>5</remote-type>
              <local-name>[Breakout Rate Value]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Rate Value</remote-alias>
              <ordinal>13</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>real</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>19</approx-count>
              <contains-null>true</contains-null>
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Rate Value Units</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Breakout Rate Value Units]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Rate Value Units</remote-alias>
              <ordinal>14</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>Breakout Unstable</remote-name>
              <remote-type>129</remote-type>
              <local-name>[Breakout Unstable]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>Breakout Unstable</remote-alias>
              <ordinal>15</ordinal>
              <family>indicator_data_download_20250626.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF]</object-id>
            </metadata-record>
          </metadata-records>
        </connection>
      </extract>
      <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;United States&quot;' />
      </semantic-values>
      <object-graph>
        <objects>
          <object caption='indicator_data_download_20250626.csv' id='indicator_data_download_20250626.csv_3467D2F94AEA4D2294142C8D5853A7FF'>
            <properties context=''>
              <relation connection='textscan.1fe19gz0vvtdqy14kxkh50wvw0f6' name='indicator_data_download_20250626.csv' table='[C:\Users\darry\Downloads\indicator_data_download_20250626#csv]' type='table'>
                <columns character-set='UTF-8' gridOrigin='A1:AC26:no:A1:AC26:1' header='yes' locale='en_US' separator=','>
                  <column datatype='string' name='Indicator Name' ordinal='0' />
                  <column datatype='string' name='What Is This Indicator' ordinal='1' />
                  <column datatype='string' name='Location Type' ordinal='2' />
                  <column datatype='string' name='Location' ordinal='3' />
                  <column datatype='real' name='Indicator Rate Value' ordinal='4' />
                  <column datatype='string' name='Indicator Rate Value Units' ordinal='5' />
                  <column datatype='string' name='Rate Lower Confidence Interval' ordinal='6' />
                  <column datatype='string' name='Rate Upper Confidence Interval' ordinal='7' />
                  <column datatype='string' name='Indicator Count Value' ordinal='8' />
                  <column datatype='string' name='Indicator Count Value Units' ordinal='9' />
                  <column datatype='string' name='Count Lower Confidence Interval' ordinal='10' />
                  <column datatype='string' name='Count Upper Confidence Interval' ordinal='11' />
                  <column datatype='string' name='Indicator Value Unstable' ordinal='12' />
                  <column datatype='date' date-parse-format='yyyy' name='Period of Measure' ordinal='13' />
                  <column datatype='string' name='Data Source' ordinal='14' />
                  <column datatype='string' name='Technical Note' ordinal='15' />
                  <column datatype='string' name='Breakout Title' ordinal='16' />
                  <column datatype='string' name='Breakout Category' ordinal='17' />
                  <column datatype='string' name='Breakout Subcategory' ordinal='18' />
                  <column datatype='real' name='Breakout Rate Value' ordinal='19' />
                  <column datatype='string' name='Breakout Rate Value Units' ordinal='20' />
                  <column datatype='string' name='Breakout Rate Lower Confidence Interval' ordinal='21' />
                  <column datatype='string' name='Breakout Rate Upper Confidence Interval' ordinal='22' />
                  <column datatype='string' name='Breakout Count Value' ordinal='23' />
                  <column datatype='string' name='Breakout Count Value Units' ordinal='24' />
                  <column datatype='string' name='Breakout Count Lower Confidence Interval' ordinal='25' />
                  <column datatype='string' name='Breakout Count Upper Confidence Interval' ordinal='26' />
                  <column datatype='string' name='Breakout Unstable' ordinal='27' />
                  <column datatype='string' name='Breakout Footer' ordinal='28' />
                </columns>
              </relation>
            </properties>
            <properties context='extract'>
              <relation name='Extract' table='[Extract].[Extract]' type='table' />
            </properties>
          </object>
        </objects>
      </object-graph>
    </datasource>
  </datasources>
  <worksheets>
    <worksheet name='Category Percent Breakdown'>
      <table>
        <view>
          <datasources>
            <datasource caption='indicator_data_download_20250626' name='federated.1p52r7z1tcber311vk12z17mlny8' />
          </datasources>
          <datasource-dependencies datasource='federated.1p52r7z1tcber311vk12z17mlny8'>
            <column datatype='real' name='[Breakout Rate Value]' role='measure' type='quantitative' />
            <column datatype='string' name='[Breakout Subcategory]' role='dimension' type='nominal' />
            <column-instance column='[Breakout Subcategory]' derivation='None' name='[none:Breakout Subcategory:nk]' pivot='key' type='nominal' />
            <column-instance column='[Breakout Rate Value]' derivation='Sum' name='[pcto:sum:Breakout Rate Value:qk]' pivot='key' type='quantitative'>
              <table-calc ordering-type='Rows' type='PctTotal' />
            </column-instance>
            <column-instance column='[Breakout Rate Value]' derivation='Sum' name='[sum:Breakout Rate Value:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='text-format' field='[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:qk]' value='p0.0%' />
            <format attr='text-align' data-class='subtotal' field='[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:qk]' value='center' />
            <format attr='text-orientation' data-class='subtotal' field='[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:qk]' value='0' />
            <format attr='wrap' data-class='subtotal' field='[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:qk]' value='auto' />
          </style-rule>
          <style-rule element='label'>
            <format attr='text-format' field='[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]' value='p0.00%' />
            <format attr='text-align' field='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' value='center' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Pie' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <color column='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' />
              <wedge-size column='[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]' />
              <text column='[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:qk]' />
              <text column='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='size' value='1' />
                <format attr='mark-labels-cull' value='true' />
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows />
        <cols />
      </table>
      <simple-id uuid='{EDCD281E-391E-487A-B925-3983A73B097E}' />
    </worksheet>
    <worksheet name='Spending Per Category'>
      <table>
        <view>
          <datasources>
            <datasource caption='indicator_data_download_20250626' name='federated.1p52r7z1tcber311vk12z17mlny8' />
          </datasources>
          <datasource-dependencies datasource='federated.1p52r7z1tcber311vk12z17mlny8'>
            <column datatype='real' name='[Breakout Rate Value]' role='measure' type='quantitative' />
            <column datatype='string' name='[Breakout Subcategory]' role='dimension' type='nominal' />
            <column-instance column='[Breakout Subcategory]' derivation='None' name='[none:Breakout Subcategory:nk]' pivot='key' type='nominal' />
            <column-instance column='[Breakout Rate Value]' derivation='Sum' name='[sum:Breakout Rate Value:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <computed-sort column='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' direction='ASC' using='[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]' />
          <filter class='quantitative' column='[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]' included-values='non-null' />
          <slices>
            <column>[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='height' field='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' value='79' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <style>
              <style-rule element='pane'>
                <format attr='minwidth' value='2023' />
                <format attr='maxwidth' value='2023' />
                <format attr='minheight' value='396' />
                <format attr='maxheight' value='396' />
                <format attr='aspect' value='0' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]</rows>
        <cols>[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Breakout Rate Value:qk]</cols>
      </table>
      <simple-id uuid='{A8A71B83-D83A-44F8-86CE-78038196C39F}' />
    </worksheet>
    <worksheet name='Spending Per Year'>
      <table>
        <view>
          <datasources>
            <datasource caption='indicator_data_download_20250626' name='federated.1p52r7z1tcber311vk12z17mlny8' />
          </datasources>
          <datasource-dependencies datasource='federated.1p52r7z1tcber311vk12z17mlny8'>
            <column datatype='real' name='[Indicator Rate Value]' role='measure' type='quantitative' />
            <column datatype='date' name='[Period of Measure]' role='dimension' type='ordinal' />
            <column-instance column='[Indicator Rate Value]' derivation='Sum' name='[sum:Indicator Rate Value:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Period of Measure]' derivation='Year-Trunc' name='[tyr:Period of Measure:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='field-labels-decoration'>
            <format attr='text-align' value='auto' />
            <format attr='vertical-align' value='auto' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Bar' />
          </pane>
        </panes>
        <rows>[federated.1p52r7z1tcber311vk12z17mlny8].[sum:Indicator Rate Value:qk]</rows>
        <cols>[federated.1p52r7z1tcber311vk12z17mlny8].[tyr:Period of Measure:ok]</cols>
      </table>
      <simple-id uuid='{E1109784-2846-4272-BF39-D1AEC57E9BEE}' />
    </worksheet>
  </worksheets>
  <dashboards>
    <dashboard enable-sort-zone-taborder='true' name='Category Breakdown'>
      <style />
      <size minheight='560' minwidth='420' sizing-mode='range' />
      <zones>
        <zone h='100000' id='17' type-v2='layout-basic' w='100000' x='0' y='0'>
          <zone h='98684' id='21' param='horz' type-v2='layout-flow' w='99248' x='376' y='658'>
            <zone h='98684' id='19' type-v2='layout-basic' w='99248' x='376' y='658'>
              <zone h='49342' id='16' name='Spending Per Category' w='99248' x='376' y='658'>
                <zone-style>
                  <format attr='border-color' value='#000000' />
                  <format attr='border-style' value='none' />
                  <format attr='border-width' value='0' />
                  <format attr='margin' value='4' />
                </zone-style>
              </zone>
              <zone h='49342' id='18' name='Category Percent Breakdown' w='49624' x='376' y='50000'>
                <zone-style>
                  <format attr='border-color' value='#000000' />
                  <format attr='border-style' value='none' />
                  <format attr='border-width' value='0' />
                  <format attr='margin' value='4' />
                </zone-style>
              </zone>
              <zone h='49342' id='23' name='Spending Per Year' w='49624' x='50000' y='50000'>
                <zone-style>
                  <format attr='border-color' value='#000000' />
                  <format attr='border-style' value='none' />
                  <format attr='border-width' value='0' />
                  <format attr='margin' value='4' />
                </zone-style>
              </zone>
            </zone>
          </zone>
          <zone-style>
            <format attr='border-color' value='#000000' />
            <format attr='border-style' value='none' />
            <format attr='border-width' value='0' />
            <format attr='margin' value='8' />
          </zone-style>
        </zone>
      </zones>
      <devicelayouts>
        <devicelayout name='Desktop'>
          <zones />
        </devicelayout>
        <devicelayout auto-generated='true' name='Phone'>
          <size maxheight='850' minheight='850' sizing-mode='vscroll' />
          <zones>
            <zone h='100000' id='27' type-v2='layout-basic' w='100000' x='0' y='0'>
              <zone h='98684' id='26' param='vert' type-v2='layout-flow' w='99248' x='376' y='658'>
                <zone fixed-size='268' h='49342' id='16' is-fixed='true' name='Spending Per Category' w='99248' x='376' y='658'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='268' h='49342' id='18' is-fixed='true' name='Category Percent Breakdown' w='49624' x='376' y='50000'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='268' h='49342' id='23' is-fixed='true' name='Spending Per Year' w='49624' x='50000' y='50000'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
              </zone>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='8' />
              </zone-style>
            </zone>
          </zones>
        </devicelayout>
      </devicelayouts>
      <simple-id uuid='{4074E4C8-AA99-491E-9268-D59275658820}' />
    </dashboard>
  </dashboards>
  <windows source-height='30'>
    <window class='worksheet' name='Spending Per Category'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{177A32BC-A3C8-493D-8D6F-09DA8C53C2E5}' />
    </window>
    <window class='worksheet' name='Category Percent Breakdown'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card pane-specification-id='0' param='[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]' type='color' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <zoom type='entire-view' />
        <highlight>
          <color-one-way>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[pcto:sum:Breakout Rate Value:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{E706E947-C429-472A-8AC4-A2C71FB54FCC}' />
    </window>
    <window class='worksheet' name='Spending Per Year'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <zoom type='entire-view' />
        <highlight>
          <color-one-way>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[:Measure Names]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Category:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Subcategory:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Title:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Breakout Unstable:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Data Source:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Indicator Name:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Location Type:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Location:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[none:Technical Note:nk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[tyr:Period of Measure:ok]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[tyr:Period of Measure:qk]</field>
            <field>[federated.1p52r7z1tcber311vk12z17mlny8].[yr:Period of Measure:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{628ACE7B-5A17-499E-BB9D-F743BC628C5C}' />
    </window>
    <window class='dashboard' maximized='true' name='Category Breakdown'>
      <viewpoints>
        <viewpoint name='Category Percent Breakdown'>
          <zoom type='entire-view' />
        </viewpoint>
        <viewpoint name='Spending Per Category' />
        <viewpoint name='Spending Per Year'>
          <zoom type='entire-view' />
        </viewpoint>
      </viewpoints>
      <active id='-1' />
      <simple-id uuid='{B07108C6-2009-4A7B-8E70-23E22E2D7616}' />
    </window>
  </windows>
  <thumbnails>
    <thumbnail height='192' name='Category Breakdown' width='192'>
      iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAACXBIWXMAAA7DAAAOwwHHb6hk
      AAASiklEQVR4nO3dZ3cb95XH8e8U9N4IkJRI9WpbrlFsa514T/Yt5a0kbyN5sutNHMeO13Jk
      UY2ULFZRbCBBEABJdEzZB7RkS4IsUBYo0P/7OUdHLJfA5YA/TAHujOa6rosQitJfdwNCvE4S
      AKE0CYBQmgRAKE0CIJRm/vST5YVpFlcLZEbGOXdyrKcbqG8+IO9kCGt1skNDz61bmJ5ivbRL
      IJLknTfOdq2xO3W++eYaZijBh+9fevz1cqVCIh7vqR8h9uOJAEzPLvDRp/9FwGMwdXuC7d06
      2bHTaPUiha0yp9/6gJlbV2m3LS7+5nesz96iVFgifuEPeNwWc9/foVDaIZTIkQtrLKwVCUYS
      XLp4hrW1TT749FO+/epLiqs+ZpfXGRo9ht7ZZW2lyOVPPuTWte946/IVYn6TzfwSD5bWSI+M
      c/2bf3D2wrvkEn4WltfJHT2J1iiyUdohmhpBb26xXqxw7tL7VFbmKbcgFY9wYmyYlcIO40dy
      r2v5igH3xCbQ73//Cde/+Ypvr99hu97h44+vsP5whhsTN2h32kzemcT1hLjy9gnmlpeotvy8
      ++Z5wGV1NU+xsstHH39MY7vA9FKeD3/7Po1KGQCnXePrr74iGE0zMXGDTrvF1OQk9+7e472P
      LmMCDdsl6t/LpG1Z6IbO7P05RsdPcOnN89yYuEGn02Zy6jYrGyUuv3uJUmmDzUqbT/7jQ2bv
      TXF/ZoXfvPc2hZWHzN3/Hj0YPehlKg6RJwIwOzNNIBSm3WlRrWzy3bVvMYJJhrJDRCJxzp4+
      8bhW030UCw+4fXe66w1HfTpXv71GpdbauyNviCuffMIHb18klxvCHwxz/vw54uksfnOvjXPH
      hvnv//2CazcnmZ6eRdc1AAKaxcTUzI8/d+48Jm2+/e4GjY6G1ahw/bvrBBNJsrksugaX3jjN
      15MPOZoM9mXBiV8H7aevBLuui23bmKbJ/129yuUPfoNpGk98/acc28J2dTzms/vSq4tzPFzN
      YwRSXH73wlPfdbEsG8M00Z76juPYgI6muXQsG6/Hs3f/joNp6I9/7sHMPdby60RyJ3jrzBjN
      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
      1MP3Ai0nAAAAAElFTkSuQmCC
    </thumbnail>
    <thumbnail height='192' name='Category Percent Breakdown' width='192'>
      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
      0l9WxQoAAAAASUVORK5CYII=
    </thumbnail>
    <thumbnail height='192' name='Spending Per Category' width='192'>
      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
    </thumbnail>
    <thumbnail height='192' name='Spending Per Year' width='192'>
      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
      TkSuQmCC
    </thumbnail>
  </thumbnails>
</workbook>
