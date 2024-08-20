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
# Warmup Iteration   1: 1.766 ops/ms
Iteration   1: 7.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.241 ops/ms


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
# Warmup Iteration   1: 6.312 ops/ms
Iteration   1: 9.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.442 ops/ms


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
# Warmup Iteration   1: 4.903 ops/ms
Iteration   1: 13.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.361 ops/ms


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
# Warmup Iteration   1: 5.131 ops/ms
Iteration   1: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.433 ops/ms


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.075 ms/op
Iteration   1: 2.201 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.201 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.046 ms/op
Iteration   1: 1.936 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.936 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.046 ms/op
Iteration   1: 2.324 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.324 ms/op


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
# Warmup Iteration   1: 4.869 ±(99.9%) 0.098 ms/op
Iteration   1: 3.699 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.699 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.080 ms/op
Iteration   1: 2.336 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   8.875 ms/op
                 createUser·p0.999:  36.700 ms/op
                 createUser·p0.9999: 37.200 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13677
  mean =      2.336 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10700 
    [ 2.500,  5.000) = 2699 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.375 ms/op
     p(99.0000) =      8.875 ms/op
     p(99.9000) =     36.700 ms/op
     p(99.9900) =     37.200 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.060 ms/op
Iteration   1: 2.043 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.427 ms/op
                 existUser·p0.50:   1.970 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.207 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 11.148 ms/op
                 existUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15685
  mean =      2.043 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 302 
    [ 1.250,  2.500) = 13773 
    [ 2.500,  3.750) = 1511 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     11.148 ms/op
     p(99.9990) =     11.158 ms/op
     p(99.9999) =     11.158 ms/op
    p(100.0000) =     11.158 ms/op


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
# Warmup Iteration   1: 3.416 ±(99.9%) 0.082 ms/op
Iteration   1: 1.916 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 11.790 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16800
  mean =      1.916 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 536 
    [ 1.250,  2.500) = 15173 
    [ 2.500,  3.750) = 836 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     11.790 ms/op
     p(99.9990) =     11.846 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


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
# Warmup Iteration   1: 4.996 ±(99.9%) 0.147 ms/op
Iteration   1: 3.262 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  29.655 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9675
  mean =      3.262 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 870 
    [ 2.500,  5.000) = 8585 
    [ 5.000,  7.500) = 179 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     29.655 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.241          ops/ms
ClientSimple.existUser                       thrpt          9.442          ops/ms
ClientSimple.getUser                         thrpt         13.361          ops/ms
ClientSimple.listUser                        thrpt          9.433          ops/ms
ClientSimple.createUser                       avgt          2.201           ms/op
ClientSimple.existUser                        avgt          1.936           ms/op
ClientSimple.getUser                          avgt          2.324           ms/op
ClientSimple.listUser                         avgt          3.699           ms/op
ClientSimple.createUser                     sample  13677   2.336 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.467           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.375           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.875           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.700           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.200           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.224           ms/op
ClientSimple.existUser                      sample  15685   2.043 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.427           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.970           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.207           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.026           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.148           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.158           ms/op
ClientSimple.getUser                        sample  16800   1.916 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.169           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.502           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.790           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.846           ms/op
ClientSimple.listUser                       sample   9675   3.262 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.655           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.540           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.540           ms/op

Benchmark result is saved to 1724134408451.json
