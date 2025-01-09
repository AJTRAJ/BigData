# BigData
Summary Table:
Format	  Type	Best For	Compression	Readability	Schema Evolution
CSV	      Text	Simple exchanges	Low	High	None
JSON	    Semi-structured	APIs, nested data	Low	High	None
Parquet	  Columnar	Analytical queries	High	Low	Moderate
Avro	    Row-based	Streaming, serialization	Medium	Low	Excellent
ORC	      Columnar	Hive-based analytics	High	Low	Moderate
Sequence	Row-based	Hadoop intermediate storage	Medium	Low	None
RCFile	  Hybrid	Early Hive workloads	Medium	Low	None
