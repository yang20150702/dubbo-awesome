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
# Warmup Iteration   1: 1.638 ops/ms
Iteration   1: 6.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.446 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.375 ops/ms
Iteration   1: 11.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.900 ops/ms


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
# Warmup Iteration   1: 5.582 ops/ms
Iteration   1: 12.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.954 ops/ms


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
# Warmup Iteration   1: 5.082 ops/ms
Iteration   1: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.273 ops/ms


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.065 ms/op
Iteration   1: 2.120 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.120 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.055 ms/op
Iteration   1: 1.905 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.075 ms/op
Iteration   1: 2.317 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.317 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.083 ms/op
Iteration   1: 3.349 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.349 ms/op


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.100 ms/op
Iteration   1: 2.466 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.378 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   12.529 ms/op
                 createUser·p0.999:  27.754 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13029
  mean =      2.466 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9287 
    [ 2.500,  5.000) = 3482 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =     12.529 ms/op
     p(99.9000) =     27.754 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.066 ms/op
Iteration   1: 1.865 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.039 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 13.802 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17200
  mean =      1.865 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 925 
    [ 1.250,  2.500) = 15069 
    [ 2.500,  3.750) = 1142 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.039 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     13.802 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.083 ms/op
Iteration   1: 2.031 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   1.808 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.892 ms/op
                 getUser·p0.99:   3.437 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 20.127 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15741
  mean =      2.031 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13199 
    [ 2.500,  5.000) = 2478 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      3.437 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     20.127 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.163 ms/op
Iteration   1: 3.265 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.787 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9790
  mean =      3.265 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 680 
    [ 2.500,  3.750) = 7392 
    [ 3.750,  5.000) = 1415 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.787 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.446          ops/ms
ClientSimple.existUser                       thrpt         11.900          ops/ms
ClientSimple.getUser                         thrpt         12.954          ops/ms
ClientSimple.listUser                        thrpt          9.273          ops/ms
ClientSimple.createUser                       avgt          2.120           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          2.317           ms/op
ClientSimple.listUser                         avgt          3.349           ms/op
ClientSimple.createUser                     sample  13029   2.466 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.378           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.146           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.529           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.754           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.853           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.853           ms/op
ClientSimple.existUser                      sample  17200   1.865 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.039           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.533           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.802           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.861           ms/op
ClientSimple.getUser                        sample  15741   2.031 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.592           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.808           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.437           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.366           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.127           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.447           ms/op
ClientSimple.listUser                       sample   9790   3.265 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.108           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.116           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.787           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.990           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.990           ms/op

Benchmark result is saved to 1724479961070.json
