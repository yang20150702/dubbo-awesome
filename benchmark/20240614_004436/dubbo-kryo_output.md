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
# Warmup Iteration   1: 1.712 ops/ms
Iteration   1: 6.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.881 ops/ms


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
# Warmup Iteration   1: 5.437 ops/ms
Iteration   1: 11.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.470 ops/ms


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
# Warmup Iteration   1: 6.059 ops/ms
Iteration   1: 13.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.248 ops/ms


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
# Warmup Iteration   1: 3.782 ops/ms
Iteration   1: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.825 ops/ms


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
# Warmup Iteration   1: 4.879 ±(99.9%) 0.106 ms/op
Iteration   1: 2.267 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.267 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.072 ms/op
Iteration   1: 2.276 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.276 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.078 ms/op
Iteration   1: 2.106 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.106 ms/op


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.128 ms/op
Iteration   1: 3.623 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.623 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.112 ms/op
Iteration   1: 2.760 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   11.178 ms/op
                 createUser·p0.999:  21.350 ms/op
                 createUser·p0.9999: 22.987 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11585
  mean =      2.760 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4686 
    [ 2.500,  5.000) = 6723 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =     11.178 ms/op
     p(99.9000) =     21.350 ms/op
     p(99.9900) =     22.987 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.067 ms/op
Iteration   1: 1.713 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.390 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.021 ms/op
                 existUser·p0.95:   2.253 ms/op
                 existUser·p0.99:   3.246 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18653
  mean =      1.713 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 17863 
    [ 2.500,  3.750) = 437 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.021 ms/op
     p(95.0000) =      2.253 ms/op
     p(99.0000) =      3.246 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.089 ms/op
Iteration   1: 2.054 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.699 ms/op
                 getUser·p0.99:   3.755 ms/op
                 getUser·p0.999:  12.803 ms/op
                 getUser·p0.9999: 12.934 ms/op
                 getUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15575
  mean =      2.054 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 13033 
    [ 2.500,  3.750) = 2124 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.755 ms/op
     p(99.9000) =     12.803 ms/op
     p(99.9900) =     12.934 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


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
# Warmup Iteration   1: 4.673 ±(99.9%) 0.131 ms/op
Iteration   1: 3.149 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   2.818 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   4.874 ms/op
                 listUser·p0.999:  22.053 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10149
  mean =      3.149 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1230 
    [ 2.500,  5.000) = 8840 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.881          ops/ms
ClientSimple.existUser                       thrpt         11.470          ops/ms
ClientSimple.getUser                         thrpt         13.248          ops/ms
ClientSimple.listUser                        thrpt          7.825          ops/ms
ClientSimple.createUser                       avgt          2.267           ms/op
ClientSimple.existUser                        avgt          2.276           ms/op
ClientSimple.getUser                          avgt          2.106           ms/op
ClientSimple.listUser                         avgt          3.623           ms/op
ClientSimple.createUser                     sample  11585   2.760 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.391           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.383           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.617           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.178           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.350           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.987           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.101           ms/op
ClientSimple.existUser                      sample  18653   1.713 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.390           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.021           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.246           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.091           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.911           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.911           ms/op
ClientSimple.getUser                        sample  15575   2.054 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.755           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.803           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.934           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.943           ms/op
ClientSimple.listUser                       sample  10149   3.149 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.110           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.818           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.053           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.151           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.151           ms/op

Benchmark result is saved to 1718325630819.json
