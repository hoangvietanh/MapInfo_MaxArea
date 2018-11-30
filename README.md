# MapInfo_MaxArea

- Identify forest type of largest polygon that share the same owner_id
- The purpose is then to update all other polygon of the same owner with the forest type of the largest one >> avoiding one small land parcel have too many forst type.
- Normally this will be applied for polygon smaller than a threshold
- MapInfo file attached to run test.
- The SQL can be applied in similar problem where we need to select records that have max value from a table that have repeated unique ID

