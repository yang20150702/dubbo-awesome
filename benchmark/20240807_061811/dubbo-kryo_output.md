# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.748 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.994 ops/ms
Iteration   1: 13.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.563 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ops/ms
Iteration   1: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.840 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.588 ops/ms
Iteration   1: 8.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.609 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ±(99.9%) 0.087 ms/op
Iteration   1: 2.237 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.091 ±(99.9%) 0.053 ms/op
Iteration   1: 1.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ±(99.9%) 0.053 ms/op
Iteration   1: 2.062 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.788 ±(99.9%) 0.095 ms/op
Iteration   1: 3.251 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.251 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.084 ms/op
Iteration   1: 2.189 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14592
  mean =      2.189 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 10980 
    [ 2.500,  3.750) = 3213 
    [ 3.750,  5.000) = 226 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ±(99.9%) 0.071 ms/op
Iteration   1: 1.896 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 11.833 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16849
  mean =      1.896 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 569 
    [ 1.250,  2.500) = 15054 
    [ 2.500,  3.750) = 1032 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     11.833 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.303 ±(99.9%) 0.077 ms/op
Iteration   1: 2.100 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  16.282 ms/op
                 getUser·p0.9999: 16.572 ms/op
                 getUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15246
  mean =      2.100 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 13534 
    [ 2.500,  3.750) = 1307 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     16.282 ms/op
     p(99.9900) =     16.572 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.124 ms/op
Iteration   1: 3.514 ±(99.9%) 0.201 ms/op
                 listUser·p0.00:   0.612 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.126 ms/op
                 listUser·p0.999:  106.810 ms/op
                 listUser·p0.9999: 121.373 ms/op
                 listUser·p1.00:   121.373 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9105
  mean =      3.514 ±(99.9%) 0.201 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 9053 
    [ 12.500,  25.000) = 11 
    [ 25.000,  37.500) = 5 
    [ 37.500,  50.000) = 4 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 8 
    [100.000, 112.500) = 11 
    [112.500, 125.000) = 5 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.126 ms/op
     p(99.9000) =    106.810 ms/op
     p(99.9900) =    121.373 ms/op
     p(99.9990) =    121.373 ms/op
     p(99.9999) =    121.373 ms/op
    p(100.0000) =    121.373 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.748          ops/ms
ClientSimple.existUser                       thrpt          13.563          ops/ms
ClientSimple.getUser                         thrpt          12.840          ops/ms
ClientSimple.listUser                        thrpt           8.609          ops/ms
ClientSimple.createUser                       avgt           2.237           ms/op
ClientSimple.existUser                        avgt           1.932           ms/op
ClientSimple.getUser                          avgt           2.062           ms/op
ClientSimple.listUser                         avgt           3.251           ms/op
ClientSimple.createUser                     sample  14592    2.189 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.694           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample           4.899           ms/op
ClientSimple.createUser:createUser·p0.999   sample          14.582           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          18.547           ms/op
ClientSimple.createUser:createUser·p1.00    sample          18.547           ms/op
ClientSimple.existUser                      sample  16849    1.896 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.490           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.776           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.239           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          11.833           ms/op
ClientSimple.existUser:existUser·p1.00      sample          11.911           ms/op
ClientSimple.getUser                        sample  15246    2.100 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.590           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.366           ms/op
ClientSimple.getUser:getUser·p0.999         sample          16.282           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          16.572           ms/op
ClientSimple.getUser:getUser·p1.00          sample          16.581           ms/op
ClientSimple.listUser                       sample   9105    3.514 ± 0.201   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.612           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.126           ms/op
ClientSimple.listUser:listUser·p0.999       sample         106.810           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         121.373           ms/op
ClientSimple.listUser:listUser·p1.00        sample         121.373           ms/op

Benchmark result is saved to 1723011224115.json
