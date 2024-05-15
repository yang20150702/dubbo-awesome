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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 6.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.879 ops/ms


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
# Warmup Iteration   1: 5.154 ops/ms
Iteration   1: 11.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.673 ops/ms


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
# Warmup Iteration   1: 5.381 ops/ms
Iteration   1: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.238 ops/ms


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
# Warmup Iteration   1: 5.098 ops/ms
Iteration   1: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.208 ops/ms


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.065 ms/op
Iteration   1: 2.186 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.041 ms/op
Iteration   1: 1.973 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.063 ms/op
Iteration   1: 2.240 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.240 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.090 ms/op
Iteration   1: 3.671 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.671 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ±(99.9%) 0.086 ms/op
Iteration   1: 2.172 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.462 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   6.547 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 19.546 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14990
  mean =      2.172 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 13550 
    [ 2.500,  3.750) = 1081 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      6.547 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     19.546 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 2.924 ±(99.9%) 0.067 ms/op
Iteration   1: 1.866 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   6.060 ms/op
                 existUser·p0.999:  12.755 ms/op
                 existUser·p0.9999: 14.114 ms/op
                 existUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17130
  mean =      1.866 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 770 
    [ 1.250,  2.500) = 14808 
    [ 2.500,  3.750) = 1288 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      6.060 ms/op
     p(99.9000) =     12.755 ms/op
     p(99.9900) =     14.114 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.120 ms/op
Iteration   1: 1.925 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  11.518 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16644
  mean =      1.925 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 892 
    [ 1.250,  2.500) = 14094 
    [ 2.500,  3.750) = 1460 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     11.764 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.115 ms/op
Iteration   1: 3.737 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.445 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  62.485 ms/op
                 listUser·p0.9999: 65.667 ms/op
                 listUser·p1.00:   65.667 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8559
  mean =      3.737 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8166 
    [ 5.000, 10.000) = 299 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     62.485 ms/op
     p(99.9900) =     65.667 ms/op
     p(99.9990) =     65.667 ms/op
     p(99.9999) =     65.667 ms/op
    p(100.0000) =     65.667 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.879          ops/ms
ClientSimple.existUser                       thrpt         11.673          ops/ms
ClientSimple.getUser                         thrpt         10.238          ops/ms
ClientSimple.listUser                        thrpt          8.208          ops/ms
ClientSimple.createUser                       avgt          2.186           ms/op
ClientSimple.existUser                        avgt          1.973           ms/op
ClientSimple.getUser                          avgt          2.240           ms/op
ClientSimple.listUser                         avgt          3.671           ms/op
ClientSimple.createUser                     sample  14990   2.172 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.462           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.547           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.252           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.546           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.595           ms/op
ClientSimple.existUser                      sample  17130   1.866 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.673           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.793           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.060           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.755           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.114           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.172           ms/op
ClientSimple.getUser                        sample  16644   1.925 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.871           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.981           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.518           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.764           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.796           ms/op
ClientSimple.listUser                       sample   8559   3.737 ± 0.127   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.760           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.445           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.207           ms/op
ClientSimple.listUser:listUser·p0.999       sample         62.485           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         65.667           ms/op
ClientSimple.listUser:listUser·p1.00        sample         65.667           ms/op

Benchmark result is saved to 1715733549960.json
