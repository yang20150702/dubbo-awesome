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
# Warmup Iteration   1: 1.897 ops/ms
Iteration   1: 6.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.681 ops/ms


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
# Warmup Iteration   1: 4.745 ops/ms
Iteration   1: 11.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.465 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ops/ms
Iteration   1: 14.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.392 ops/ms


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
# Warmup Iteration   1: 5.488 ops/ms
Iteration   1: 8.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.705 ops/ms


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.074 ms/op
Iteration   1: 2.084 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.084 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.058 ms/op
Iteration   1: 2.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.035 ms/op


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
# Warmup Iteration   1: 3.435 ±(99.9%) 0.067 ms/op
Iteration   1: 2.154 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.154 ms/op


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
# Warmup Iteration   1: 5.131 ±(99.9%) 0.111 ms/op
Iteration   1: 3.415 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.415 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.120 ms/op
Iteration   1: 2.528 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.343 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   11.838 ms/op
                 createUser·p0.999:  23.071 ms/op
                 createUser·p0.9999: 33.498 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12638
  mean =      2.528 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8250 
    [ 2.500,  5.000) = 4138 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.343 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =     11.838 ms/op
     p(99.9000) =     23.071 ms/op
     p(99.9900) =     33.498 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.078 ms/op
Iteration   1: 2.006 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.900 ms/op
                 existUser·p0.999:  15.811 ms/op
                 existUser·p0.9999: 15.899 ms/op
                 existUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15989
  mean =      2.006 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 694 
    [ 1.250,  2.500) = 13952 
    [ 2.500,  3.750) = 1180 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.900 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     15.899 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.082 ms/op
Iteration   1: 1.951 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   1.849 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.548 ms/op
                 getUser·p0.99:   4.201 ms/op
                 getUser·p0.999:  11.980 ms/op
                 getUser·p0.9999: 12.304 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16412
  mean =      1.951 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 312 
    [ 1.250,  2.500) = 15117 
    [ 2.500,  3.750) = 791 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.201 ms/op
     p(99.9000) =     11.980 ms/op
     p(99.9900) =     12.304 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.127 ms/op
Iteration   1: 3.627 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  6.319 ms/op
                 listUser·p0.9999: 7.070 ms/op
                 listUser·p1.00:   7.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8888
  mean =      3.627 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 82 
    [2.000, 2.500) = 470 
    [2.500, 3.000) = 1061 
    [3.000, 3.500) = 1615 
    [3.500, 4.000) = 3223 
    [4.000, 4.500) = 1818 
    [4.500, 5.000) = 331 
    [5.000, 5.500) = 154 
    [5.500, 6.000) = 93 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      6.319 ms/op
     p(99.9900) =      7.070 ms/op
     p(99.9990) =      7.070 ms/op
     p(99.9999) =      7.070 ms/op
    p(100.0000) =      7.070 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.681          ops/ms
ClientSimple.existUser                       thrpt         11.465          ops/ms
ClientSimple.getUser                         thrpt         14.392          ops/ms
ClientSimple.listUser                        thrpt          8.705          ops/ms
ClientSimple.createUser                       avgt          2.084           ms/op
ClientSimple.existUser                        avgt          2.035           ms/op
ClientSimple.getUser                          avgt          2.154           ms/op
ClientSimple.listUser                         avgt          3.415           ms/op
ClientSimple.createUser                     sample  12638   2.528 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.862           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.343           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.224           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.838           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.071           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.498           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.897           ms/op
ClientSimple.existUser                      sample  15989   2.006 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.811           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.899           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.909           ms/op
ClientSimple.getUser                        sample  16412   1.951 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.618           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.849           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.201           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.980           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.304           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.304           ms/op
ClientSimple.listUser                       sample   8888   3.627 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.807           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.686           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.546           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.319           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.070           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.070           ms/op

Benchmark result is saved to 1719382406750.json
