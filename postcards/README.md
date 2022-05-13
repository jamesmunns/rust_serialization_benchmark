## `log`

This data set is composed of HTTP request logs that are small and contain many strings.

### Raw Data

For operations, time per iteration; for size, bytes. Lower is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 573.46 us | 2.8985 ms | 765778 | 312739 | 264630 |
| postcard-all-varints | 665.27 us | 3.0808 ms | 724953 | 303462 | 253747 |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


### Comparison

Relative to best. Higher is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 100.00% | 100.00% | 94.67% | 97.03% | 95.89% |
| postcard-all-varints | 86.20% | 94.08% | 100.00% | 100.00% | 100.00% |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


## `mesh`

This data set is a single mesh. The mesh contains an array of triangles, each of which has three vertices and a normal vector.

### Raw Data

For operations, time per iteration; for size, bytes. Lower is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 5.3132 ms | 7.1710 ms | 6000003 | 5380817 | 5345900 |
| postcard-all-varints | 5.4014 ms | 7.0722 ms | 6000003 | 5380817 | 5345900 |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


### Comparison

Relative to best. Higher is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 100.00% | 98.62% | 100.00% | 100.00% | 100.00% |
| postcard-all-varints | 98.37% | 100.00% | 100.00% | 100.00% | 100.00% |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


## `minecraft_savedata`

This data set is composed of Minecraft player saves that contain highly structured data.

### Raw Data

For operations, time per iteration; for size, bytes. Lower is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 593.32 us | 2.5196 ms | 356311 | 213270 | 198488 |
| postcard-all-varints | 611.62 us | 2.6194 ms | 367489 | 222144 | 207344 |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


### Comparison

Relative to best. Higher is better.

#### Serialize / deserialize speed and size

| Format / Lib | Serialize | Deserialize | Size | Zlib | Zstd |
|---|--:|--:|--:|--:|--:|
| postcard | 100.00% | 100.00% | 100.00% | 100.00% | 100.00% |
| postcard-all-varints | 97.01% | 96.19% | 96.96% | 96.01% | 95.73% |

#### Zero-copy deserialization speed

| Format / Lib | Access | Read | Update |
|---|--:|--:|--:|


