# MapInfo_MaxArea

- Identify forest type of largest polygon that share the same owner_id
- The purpose is then to update all other polygon of the same owner with the forest type of the largest one >> avoiding one small land parcel have too many forst type.
- Normally this will be applied for polygon smaller than a threshold
- MapInfo file attached to run test.
- The SQL can be applied in similar problem where we need to select records that have max value from a records that have the same identifier.

Example.

Given this table

  id      area(ha)
  a1      12
  a1      10
  a1      30 
  a2      1
  a2      3
  a2      2

The query should return

  id      area(ha)
  a1      30
  a2      3
