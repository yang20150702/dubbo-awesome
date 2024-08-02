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
# Warmup Iteration   1: 1.108 ops/ms
Iteration   1: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.556 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.495 ops/ms
Iteration   1: 12.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.244 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.965 ops/ms
Iteration   1: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.797 ops/ms


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
# Warmup Iteration   1: 4.534 ops/ms
Iteration   1: 7.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.865 ops/ms


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.071 ms/op
Iteration   1: 2.152 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.152 ms/op


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.060 ms/op
Iteration   1: 1.902 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.902 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.073 ms/op
Iteration   1: 2.149 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.149 ms/op


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.101 ms/op
Iteration   1: 3.778 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.778 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.079 ms/op
Iteration   1: 2.194 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.062 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  13.835 ms/op
                 createUser·p0.9999: 14.872 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14566
  mean =      2.194 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 11242 
    [ 2.500,  3.750) = 3007 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     13.835 ms/op
     p(99.9900) =     14.872 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.071 ms/op
Iteration   1: 1.956 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.904 ms/op
                 existUser·p0.99:   5.178 ms/op
                 existUser·p0.999:  40.082 ms/op
                 existUser·p0.9999: 41.417 ms/op
                 existUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16389
  mean =      1.956 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16195 
    [ 5.000, 10.000) = 129 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      5.178 ms/op
     p(99.9000) =     40.082 ms/op
     p(99.9900) =     41.417 ms/op
     p(99.9990) =     41.878 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.072 ms/op
Iteration   1: 1.987 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   1.864 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.433 ms/op
                 getUser·p0.999:  11.516 ms/op
                 getUser·p0.9999: 12.131 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16097
  mean =      1.987 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 14391 
    [ 2.500,  3.750) = 1483 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.433 ms/op
     p(99.9000) =     11.516 ms/op
     p(99.9900) =     12.131 ms/op
     p(99.9990) =     12.321 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.119 ms/op
Iteration   1: 3.398 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.198 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.384 ms/op
                 listUser·p0.999:  19.317 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9485
  mean =      3.398 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 441 
    [ 2.500,  5.000) = 8852 
    [ 5.000,  7.500) = 150 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.198 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.384 ms/op
     p(99.9000) =     19.317 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.556          ops/ms
ClientSimple.existUser                       thrpt         12.244          ops/ms
ClientSimple.getUser                         thrpt         12.797          ops/ms
ClientSimple.listUser                        thrpt          7.865          ops/ms
ClientSimple.createUser                       avgt          2.152           ms/op
ClientSimple.existUser                        avgt          1.902           ms/op
ClientSimple.getUser                          avgt          2.149           ms/op
ClientSimple.listUser                         avgt          3.778           ms/op
ClientSimple.createUser                     sample  14566   2.194 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.765           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.062           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.415           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.835           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.872           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.909           ms/op
ClientSimple.existUser                      sample  16389   1.956 ± 0.048   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.567           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.677           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.904           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.178           ms/op
ClientSimple.existUser:existUser·p0.999     sample         40.082           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         41.417           ms/op
ClientSimple.existUser:existUser·p1.00      sample         41.878           ms/op
ClientSimple.getUser                        sample  16097   1.987 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.566           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.864           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.433           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.516           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.131           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.321           ms/op
ClientSimple.listUser                       sample   9485   3.398 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.280           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.260           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.198           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.384           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.873           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.873           ms/op

Benchmark result is saved to 1722601009461.json
