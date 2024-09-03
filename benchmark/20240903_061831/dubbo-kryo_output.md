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
# Warmup Iteration   1: 1.679 ops/ms
Iteration   1: 6.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.797 ops/ms


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
# Warmup Iteration   1: 5.067 ops/ms
Iteration   1: 11.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.357 ops/ms


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
# Warmup Iteration   1: 5.183 ops/ms
Iteration   1: 11.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.434 ops/ms


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
# Warmup Iteration   1: 4.864 ops/ms
Iteration   1: 9.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.003 ops/ms


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.089 ms/op
Iteration   1: 2.102 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.102 ms/op


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
# Warmup Iteration   1: 3.376 ±(99.9%) 0.058 ms/op
Iteration   1: 1.995 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.995 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.101 ms/op
Iteration   1: 2.469 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.469 ms/op


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
# Warmup Iteration   1: 4.994 ±(99.9%) 0.085 ms/op
Iteration   1: 3.556 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.556 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.092 ms/op
Iteration   1: 2.307 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.781 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   7.343 ms/op
                 createUser·p0.999:  38.011 ms/op
                 createUser·p0.9999: 38.937 ms/op
                 createUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13865
  mean =      2.307 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10989 
    [ 2.500,  5.000) = 2667 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      7.343 ms/op
     p(99.9000) =     38.011 ms/op
     p(99.9900) =     38.937 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.095 ms/op
Iteration   1: 1.867 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.186 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 12.535 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17238
  mean =      1.867 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 16389 
    [ 2.500,  3.750) = 626 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.186 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     12.535 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.087 ms/op
Iteration   1: 2.044 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.494 ms/op
                 getUser·p0.50:   1.839 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.895 ms/op
                 getUser·p0.99:   3.948 ms/op
                 getUser·p0.999:  32.886 ms/op
                 getUser·p0.9999: 33.902 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15703
  mean =      2.044 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13640 
    [ 2.500,  5.000) = 1964 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.895 ms/op
     p(99.0000) =      3.948 ms/op
     p(99.9000) =     32.886 ms/op
     p(99.9900) =     33.902 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.163 ms/op
Iteration   1: 3.371 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.080 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.765 ms/op
                 listUser·p0.99:   8.218 ms/op
                 listUser·p0.999:  19.317 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9486
  mean =      3.371 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 848 
    [ 2.500,  3.750) = 6321 
    [ 3.750,  5.000) = 1957 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.765 ms/op
     p(99.0000) =      8.218 ms/op
     p(99.9000) =     19.317 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.797          ops/ms
ClientSimple.existUser                       thrpt         11.357          ops/ms
ClientSimple.getUser                         thrpt         11.434          ops/ms
ClientSimple.listUser                        thrpt          9.003          ops/ms
ClientSimple.createUser                       avgt          2.102           ms/op
ClientSimple.existUser                        avgt          1.995           ms/op
ClientSimple.getUser                          avgt          2.469           ms/op
ClientSimple.listUser                         avgt          3.556           ms/op
ClientSimple.createUser                     sample  13865   2.307 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.697           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.343           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.011           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.937           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.191           ms/op
ClientSimple.existUser                      sample  17238   1.867 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.186           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.878           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.535           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.583           ms/op
ClientSimple.getUser                        sample  15703   2.044 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.494           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.839           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.895           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         32.886           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         33.902           ms/op
ClientSimple.getUser:getUser·p1.00          sample         34.275           ms/op
ClientSimple.listUser                       sample   9486   3.371 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.080           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.765           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.218           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.317           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.562           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.562           ms/op

Benchmark result is saved to 1725344053595.json
