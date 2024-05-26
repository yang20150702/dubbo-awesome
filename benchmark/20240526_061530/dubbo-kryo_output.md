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
# Warmup Iteration   1: 2.105 ops/ms
Iteration   1: 7.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.376 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.472 ops/ms
Iteration   1: 11.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.504 ops/ms


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
# Warmup Iteration   1: 4.677 ops/ms
Iteration   1: 11.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.055 ops/ms


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
# Warmup Iteration   1: 4.990 ops/ms
Iteration   1: 8.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.362 ops/ms


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.068 ms/op
Iteration   1: 2.350 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.350 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.070 ms/op
Iteration   1: 1.988 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.988 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.058 ms/op
Iteration   1: 1.806 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.806 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.086 ms/op
Iteration   1: 3.711 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.711 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.080 ms/op
Iteration   1: 2.235 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   2.091 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   6.115 ms/op
                 createUser·p0.999:  25.616 ms/op
                 createUser·p0.9999: 25.906 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14259
  mean =      2.235 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12090 
    [ 2.500,  5.000) = 1999 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      6.115 ms/op
     p(99.9000) =     25.616 ms/op
     p(99.9900) =     25.906 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.095 ms/op
Iteration   1: 2.178 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.130 ms/op
                 existUser·p0.90:   2.712 ms/op
                 existUser·p0.95:   2.867 ms/op
                 existUser·p0.99:   3.964 ms/op
                 existUser·p0.999:  12.293 ms/op
                 existUser·p0.9999: 14.264 ms/op
                 existUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14681
  mean =      2.178 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 303 
    [ 1.250,  2.500) = 11252 
    [ 2.500,  3.750) = 2975 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.964 ms/op
     p(99.9000) =     12.293 ms/op
     p(99.9900) =     14.264 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.101 ms/op
Iteration   1: 2.136 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   1.989 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   5.515 ms/op
                 getUser·p0.999:  12.468 ms/op
                 getUser·p0.9999: 15.598 ms/op
                 getUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15037
  mean =      2.136 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 12255 
    [ 2.500,  3.750) = 2376 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.515 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     15.598 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.192 ms/op
Iteration   1: 3.612 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.311 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8855
  mean =      3.612 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 605 
    [ 2.500,  3.750) = 4479 
    [ 3.750,  5.000) = 3376 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.311 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.376          ops/ms
ClientSimple.existUser                       thrpt         11.504          ops/ms
ClientSimple.getUser                         thrpt         11.055          ops/ms
ClientSimple.listUser                        thrpt          8.362          ops/ms
ClientSimple.createUser                       avgt          2.350           ms/op
ClientSimple.existUser                        avgt          1.988           ms/op
ClientSimple.getUser                          avgt          1.806           ms/op
ClientSimple.listUser                         avgt          3.711           ms/op
ClientSimple.createUser                     sample  14259   2.235 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.459           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.091           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.115           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.616           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.906           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.919           ms/op
ClientSimple.existUser                      sample  14681   2.178 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.867           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.964           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.293           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.264           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.287           ms/op
ClientSimple.getUser                        sample  15037   2.136 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.717           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.989           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.515           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.598           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.646           ms/op
ClientSimple.listUser                       sample   8855   3.612 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.745           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.311           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.302           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.579           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.579           ms/op

Benchmark result is saved to 1716703893714.json
