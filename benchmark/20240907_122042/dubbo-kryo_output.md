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
# Warmup Iteration   1: 1.753 ops/ms
Iteration   1: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.443 ops/ms


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
# Warmup Iteration   1: 6.629 ops/ms
Iteration   1: 14.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.253 ops/ms


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
# Warmup Iteration   1: 6.038 ops/ms
Iteration   1: 13.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.507 ops/ms


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
# Warmup Iteration   1: 5.569 ops/ms
Iteration   1: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.505 ops/ms


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.079 ms/op
Iteration   1: 2.122 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.104 ms/op
Iteration   1: 1.927 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.927 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.059 ms/op
Iteration   1: 2.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.091 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.085 ms/op
Iteration   1: 3.706 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.706 ms/op


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
# Warmup Iteration   1: 3.595 ±(99.9%) 0.096 ms/op
Iteration   1: 2.455 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   2.396 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   6.362 ms/op
                 createUser·p0.999:  17.560 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13120
  mean =      2.455 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 334 
    [ 1.250,  2.500) = 7406 
    [ 2.500,  3.750) = 5036 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.396 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      6.362 ms/op
     p(99.9000) =     17.560 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.072 ms/op
Iteration   1: 2.010 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   4.013 ms/op
                 existUser·p0.999:  11.241 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15906
  mean =      2.010 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 319 
    [ 1.250,  2.500) = 13781 
    [ 2.500,  3.750) = 1639 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.013 ms/op
     p(99.9000) =     11.241 ms/op
     p(99.9900) =     12.161 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.098 ms/op
Iteration   1: 2.051 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  15.696 ms/op
                 getUser·p0.9999: 16.649 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15597
  mean =      2.051 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 12402 
    [ 2.500,  3.750) = 2835 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     16.649 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.136 ms/op
Iteration   1: 3.694 ±(99.9%) 0.081 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   15.090 ms/op
                 listUser·p0.999:  33.107 ms/op
                 listUser·p0.9999: 34.341 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8658
  mean =      3.694 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 590 
    [ 2.500,  5.000) = 7675 
    [ 5.000,  7.500) = 267 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =     15.090 ms/op
     p(99.9000) =     33.107 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.443          ops/ms
ClientSimple.existUser                       thrpt         14.253          ops/ms
ClientSimple.getUser                         thrpt         13.507          ops/ms
ClientSimple.listUser                        thrpt          8.505          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.927           ms/op
ClientSimple.getUser                          avgt          2.091           ms/op
ClientSimple.listUser                         avgt          3.706           ms/op
ClientSimple.createUser                     sample  13120   2.455 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.503           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.285           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.362           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.560           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.760           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.760           ms/op
ClientSimple.existUser                      sample  15906   2.010 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.013           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.241           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.161           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.239           ms/op
ClientSimple.getUser                        sample  15597   2.051 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.752           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.696           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.649           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.777           ms/op
ClientSimple.listUser                       sample   8658   3.694 ± 0.081   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.834           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.486           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample         15.090           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.107           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.341           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.341           ms/op

Benchmark result is saved to 1725711383743.json
