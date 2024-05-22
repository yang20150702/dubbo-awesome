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
# Warmup Iteration   1: 1.830 ops/ms
Iteration   1: 7.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.169 ops/ms


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
# Warmup Iteration   1: 6.719 ops/ms
Iteration   1: 12.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.121 ops/ms


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
# Warmup Iteration   1: 5.477 ops/ms
Iteration   1: 11.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.921 ops/ms


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
# Warmup Iteration   1: 4.623 ops/ms
Iteration   1: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.725 ops/ms


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.058 ms/op
Iteration   1: 2.312 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.312 ms/op


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
# Warmup Iteration   1: 2.909 ±(99.9%) 0.045 ms/op
Iteration   1: 1.769 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.769 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.053 ms/op
Iteration   1: 1.871 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.871 ms/op


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.085 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.144 ms/op


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
# Warmup Iteration   1: 3.649 ±(99.9%) 0.091 ms/op
Iteration   1: 2.163 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.410 ms/op
                 createUser·p0.50:   2.091 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.753 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  15.532 ms/op
                 createUser·p0.9999: 16.311 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15112
  mean =      2.163 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 13106 
    [ 2.500,  3.750) = 1692 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     16.311 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.085 ms/op
Iteration   1: 1.913 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.801 ms/op
                 existUser·p0.99:   3.545 ms/op
                 existUser·p0.999:  19.973 ms/op
                 existUser·p0.9999: 20.676 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16742
  mean =      1.913 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15019 
    [ 2.500,  5.000) = 1691 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.801 ms/op
     p(99.0000) =      3.545 ms/op
     p(99.9000) =     19.973 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.073 ms/op
Iteration   1: 1.933 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.216 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.343 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   3.025 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 25.595 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16552
  mean =      1.933 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15576 
    [ 2.500,  5.000) = 909 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.216 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.025 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     25.595 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 4.852 ±(99.9%) 0.142 ms/op
Iteration   1: 4.257 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.864 ms/op
                 listUser·p0.999:  8.905 ms/op
                 listUser·p0.9999: 12.550 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7511
  mean =      4.257 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 78 
    [ 2.500,  3.750) = 1268 
    [ 3.750,  5.000) = 5437 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.864 ms/op
     p(99.9000) =      8.905 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.169          ops/ms
ClientSimple.existUser                       thrpt         12.121          ops/ms
ClientSimple.getUser                         thrpt         11.921          ops/ms
ClientSimple.listUser                        thrpt          8.725          ops/ms
ClientSimple.createUser                       avgt          2.312           ms/op
ClientSimple.existUser                        avgt          1.769           ms/op
ClientSimple.getUser                          avgt          1.871           ms/op
ClientSimple.listUser                         avgt          3.144           ms/op
ClientSimple.createUser                     sample  15112   2.163 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.410           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.091           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.022           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.532           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.311           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.630           ms/op
ClientSimple.existUser                      sample  16742   1.913 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.666           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.792           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.801           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.545           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.973           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.676           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.742           ms/op
ClientSimple.getUser                        sample  16552   1.933 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.216           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.025           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.969           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.595           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.788           ms/op
ClientSimple.listUser                       sample   7511   4.257 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.311           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.210           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.864           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.905           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.550           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.550           ms/op

Benchmark result is saved to 1716358348334.json
