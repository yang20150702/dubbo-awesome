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
# Warmup Iteration   1: 1.655 ops/ms
Iteration   1: 5.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.951 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.718 ops/ms
Iteration   1: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.825 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.469 ops/ms
Iteration   1: 12.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.120 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.031 ops/ms
Iteration   1: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.924 ops/ms


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.086 ms/op
Iteration   1: 2.460 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.460 ms/op


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
# Warmup Iteration   1: 3.351 ±(99.9%) 0.063 ms/op
Iteration   1: 1.858 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.858 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.072 ms/op
Iteration   1: 2.189 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.189 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.106 ms/op
Iteration   1: 3.734 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.734 ms/op


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.093 ms/op
Iteration   1: 2.415 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   10.152 ms/op
                 createUser·p0.999:  13.497 ms/op
                 createUser·p0.9999: 14.878 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13234
  mean =      2.415 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 9021 
    [ 2.500,  3.750) = 3847 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =     10.152 ms/op
     p(99.9000) =     13.497 ms/op
     p(99.9900) =     14.878 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.074 ms/op
Iteration   1: 1.892 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  21.036 ms/op
                 existUser·p0.9999: 21.483 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17009
  mean =      1.892 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16214 
    [ 2.500,  5.000) = 697 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.293 ms/op
     p(99.9000) =     21.036 ms/op
     p(99.9900) =     21.483 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.163 ms/op
Iteration   1: 2.109 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   1.946 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  17.717 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15152
  mean =      2.109 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 13515 
    [ 2.500,  3.750) = 1166 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     17.717 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.158 ms/op
Iteration   1: 3.510 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.150 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.415 ms/op
                 listUser·p0.999:  24.523 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9121
  mean =      3.510 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 462 
    [ 2.500,  5.000) = 8267 
    [ 5.000,  7.500) = 303 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.415 ms/op
     p(99.9000) =     24.523 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.951          ops/ms
ClientSimple.existUser                       thrpt         10.825          ops/ms
ClientSimple.getUser                         thrpt         12.120          ops/ms
ClientSimple.listUser                        thrpt          8.924          ops/ms
ClientSimple.createUser                       avgt          2.460           ms/op
ClientSimple.existUser                        avgt          1.858           ms/op
ClientSimple.getUser                          avgt          2.189           ms/op
ClientSimple.listUser                         avgt          3.734           ms/op
ClientSimple.createUser                     sample  13234   2.415 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.716           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.281           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.497           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.878           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.909           ms/op
ClientSimple.existUser                      sample  17009   1.892 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.412           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.812           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.036           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.483           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.529           ms/op
ClientSimple.getUser                        sample  15152   2.109 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.641           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.946           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.717           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.088           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.088           ms/op
ClientSimple.listUser                       sample   9121   3.510 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.419           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.150           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.415           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.523           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.100           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.100           ms/op

Benchmark result is saved to 1720009048153.json
