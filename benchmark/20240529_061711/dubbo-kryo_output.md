# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.047 ops/ms
Iteration   1: 6.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.385 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.147 ops/ms
Iteration   1: 13.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.437 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ops/ms
Iteration   1: 12.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.962 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ops/ms
Iteration   1: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.469 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.090 ms/op
Iteration   1: 2.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ±(99.9%) 0.050 ms/op
Iteration   1: 1.934 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.934 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ±(99.9%) 0.054 ms/op
Iteration   1: 2.388 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.388 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.091 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.112 ms/op
Iteration   1: 2.041 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.393 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.716 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 14.938 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15676
  mean =      2.041 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 13788 
    [ 2.500,  3.750) = 1301 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     14.938 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ±(99.9%) 0.068 ms/op
Iteration   1: 2.140 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.085 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   5.639 ms/op
                 existUser·p0.999:  18.285 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15332
  mean =      2.140 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 13552 
    [ 2.500,  3.750) = 1295 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      5.639 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.292 ±(99.9%) 0.088 ms/op
Iteration   1: 2.305 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.433 ms/op
                 getUser·p0.50:   2.265 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   3.808 ms/op
                 getUser·p0.999:  17.928 ms/op
                 getUser·p0.9999: 18.108 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13884
  mean =      2.305 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 10382 
    [ 2.500,  3.750) = 3215 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.808 ms/op
     p(99.9000) =     17.928 ms/op
     p(99.9900) =     18.108 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.172 ms/op
Iteration   1: 3.193 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.281 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 26.198 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10027
  mean =      3.193 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 531 
    [ 2.500,  5.000) = 9220 
    [ 5.000,  7.500) = 210 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.281 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     26.198 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.385          ops/ms
ClientSimple.existUser                       thrpt         13.437          ops/ms
ClientSimple.getUser                         thrpt         12.962          ops/ms
ClientSimple.listUser                        thrpt          8.469          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          1.934           ms/op
ClientSimple.getUser                          avgt          2.388           ms/op
ClientSimple.listUser                         avgt          3.130           ms/op
ClientSimple.createUser                     sample  15676   2.041 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.393           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.552           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.385           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.938           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.975           ms/op
ClientSimple.existUser                      sample  15332   2.140 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.085           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.639           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.285           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.399           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.399           ms/op
ClientSimple.getUser                        sample  13884   2.305 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.433           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.808           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.928           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.108           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.121           ms/op
ClientSimple.listUser                       sample  10027   3.193 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.900           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.887           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.281           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.127           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.530           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.198           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.214           ms/op

Benchmark result is saved to 1716963171885.json
