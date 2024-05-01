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
# Warmup Iteration   1: 1.594 ops/ms
Iteration   1: 6.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.340 ops/ms


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
# Warmup Iteration   1: 5.781 ops/ms
Iteration   1: 11.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.996 ops/ms


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
# Warmup Iteration   1: 4.464 ops/ms
Iteration   1: 12.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.080 ops/ms


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
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.960 ops/ms


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.084 ms/op
Iteration   1: 2.155 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.155 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.053 ms/op
Iteration   1: 1.955 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.955 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.064 ms/op
Iteration   1: 2.199 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.199 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.087 ms/op
Iteration   1: 3.494 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.494 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.087 ms/op
Iteration   1: 2.238 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   1.969 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   7.327 ms/op
                 createUser·p0.999:  30.193 ms/op
                 createUser·p0.9999: 34.406 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14290
  mean =      2.238 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11753 
    [ 2.500,  5.000) = 2275 
    [ 5.000,  7.500) = 131 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.969 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      7.327 ms/op
     p(99.9000) =     30.193 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.070 ms/op
Iteration   1: 1.866 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.031 ms/op
                 existUser·p0.999:  26.538 ms/op
                 existUser·p0.9999: 27.418 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17130
  mean =      1.866 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16408 
    [ 2.500,  5.000) = 652 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.031 ms/op
     p(99.9000) =     26.538 ms/op
     p(99.9900) =     27.418 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.078 ms/op
Iteration   1: 1.919 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   1.839 ms/op
                 getUser·p0.90:   2.273 ms/op
                 getUser·p0.95:   2.483 ms/op
                 getUser·p0.99:   3.031 ms/op
                 getUser·p0.999:  11.950 ms/op
                 getUser·p0.9999: 12.091 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16656
  mean =      1.919 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 15698 
    [ 2.500,  3.750) = 723 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.483 ms/op
     p(99.0000) =      3.031 ms/op
     p(99.9000) =     11.950 ms/op
     p(99.9900) =     12.091 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.134 ms/op
Iteration   1: 3.174 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  7.978 ms/op
                 listUser·p0.9999: 9.142 ms/op
                 listUser·p1.00:   9.142 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10067
  mean =      3.174 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 12 
    [ 1.500,  2.000) = 136 
    [ 2.000,  2.500) = 1372 
    [ 2.500,  3.000) = 3598 
    [ 3.000,  3.500) = 1704 
    [ 3.500,  4.000) = 1932 
    [ 4.000,  4.500) = 995 
    [ 4.500,  5.000) = 163 
    [ 5.000,  5.500) = 38 
    [ 5.500,  6.000) = 71 
    [ 6.000,  6.500) = 3 
    [ 6.500,  7.000) = 1 
    [ 7.000,  7.500) = 7 
    [ 7.500,  8.000) = 28 
    [ 8.000,  8.500) = 5 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      7.978 ms/op
     p(99.9900) =      9.142 ms/op
     p(99.9990) =      9.142 ms/op
     p(99.9999) =      9.142 ms/op
    p(100.0000) =      9.142 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.340          ops/ms
ClientSimple.existUser                       thrpt         11.996          ops/ms
ClientSimple.getUser                         thrpt         12.080          ops/ms
ClientSimple.listUser                        thrpt          7.960          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          1.955           ms/op
ClientSimple.getUser                          avgt          2.199           ms/op
ClientSimple.listUser                         avgt          3.494           ms/op
ClientSimple.createUser                     sample  14290   2.238 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.529           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.969           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.327           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.193           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.406           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.406           ms/op
ClientSimple.existUser                      sample  17130   1.866 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.743           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.031           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.538           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.418           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.558           ms/op
ClientSimple.getUser                        sample  16656   1.919 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.479           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.839           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.273           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.483           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.950           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.091           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.091           ms/op
ClientSimple.listUser                       sample  10067   3.174 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.155           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.978           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.142           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.142           ms/op

Benchmark result is saved to 1714565766612.json
