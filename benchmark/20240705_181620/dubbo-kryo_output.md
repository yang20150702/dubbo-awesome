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
# Warmup Iteration   1: 2.264 ops/ms
Iteration   1: 6.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.364 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.027 ops/ms
Iteration   1: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.769 ops/ms


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
# Warmup Iteration   1: 5.736 ops/ms
Iteration   1: 12.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.099 ops/ms


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
# Warmup Iteration   1: 5.689 ops/ms
Iteration   1: 9.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.619 ops/ms


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.059 ms/op
Iteration   1: 2.231 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.231 ms/op


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
# Warmup Iteration   1: 3.535 ±(99.9%) 0.065 ms/op
Iteration   1: 1.912 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.062 ms/op
Iteration   1: 2.096 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.096 ms/op


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.136 ms/op
Iteration   1: 3.657 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.657 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.083 ms/op
Iteration   1: 2.178 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   5.608 ms/op
                 createUser·p0.999:  33.039 ms/op
                 createUser·p0.9999: 33.965 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14741
  mean =      2.178 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12797 
    [ 2.500,  5.000) = 1756 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      5.608 ms/op
     p(99.9000) =     33.039 ms/op
     p(99.9900) =     33.965 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.079 ms/op
Iteration   1: 1.842 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.142 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   2.967 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 23.578 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17354
  mean =      1.842 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16827 
    [ 2.500,  5.000) = 455 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      2.967 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     23.578 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.084 ms/op
Iteration   1: 2.021 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   1.837 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.974 ms/op
                 getUser·p0.99:   3.271 ms/op
                 getUser·p0.999:  11.706 ms/op
                 getUser·p0.9999: 11.878 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15846
  mean =      2.021 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 229 
    [ 1.250,  2.500) = 12728 
    [ 2.500,  3.750) = 2804 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      3.271 ms/op
     p(99.9000) =     11.706 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.150 ms/op
Iteration   1: 3.113 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.689 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.011 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 8.889 ms/op
                 listUser·p1.00:   8.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10307
  mean =      3.113 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 33 
    [1.500, 2.000) = 217 
    [2.000, 2.500) = 2389 
    [2.500, 3.000) = 2590 
    [3.000, 3.500) = 1955 
    [3.500, 4.000) = 2075 
    [4.000, 4.500) = 558 
    [4.500, 5.000) = 271 
    [5.000, 5.500) = 123 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.011 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =      8.889 ms/op
     p(99.9990) =      8.897 ms/op
     p(99.9999) =      8.897 ms/op
    p(100.0000) =      8.897 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.364          ops/ms
ClientSimple.existUser                       thrpt         12.769          ops/ms
ClientSimple.getUser                         thrpt         12.099          ops/ms
ClientSimple.listUser                        thrpt          9.619          ops/ms
ClientSimple.createUser                       avgt          2.231           ms/op
ClientSimple.existUser                        avgt          1.912           ms/op
ClientSimple.getUser                          avgt          2.096           ms/op
ClientSimple.listUser                         avgt          3.657           ms/op
ClientSimple.createUser                     sample  14741   2.178 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.397           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.608           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.039           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.965           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.275           ms/op
ClientSimple.existUser                      sample  17354   1.842 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.633           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.142           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.967           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.151           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.578           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.626           ms/op
ClientSimple.getUser                        sample  15846   2.021 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.535           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.837           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.271           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.706           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.878           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.878           ms/op
ClientSimple.listUser                       sample  10307   3.113 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.689           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.011           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.407           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.889           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.897           ms/op

Benchmark result is saved to 1720203136198.json
