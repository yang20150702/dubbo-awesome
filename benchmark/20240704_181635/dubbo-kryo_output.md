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
# Warmup Iteration   1: 1.682 ops/ms
Iteration   1: 7.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.430 ops/ms


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
# Warmup Iteration   1: 6.457 ops/ms
Iteration   1: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.635 ops/ms


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
# Warmup Iteration   1: 5.864 ops/ms
Iteration   1: 14.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.277 ops/ms


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
# Warmup Iteration   1: 3.615 ops/ms
Iteration   1: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.286 ops/ms


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.068 ms/op
Iteration   1: 2.334 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.334 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.052 ms/op
Iteration   1: 1.836 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.836 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.060 ms/op
Iteration   1: 1.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.994 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.092 ms/op
Iteration   1: 3.121 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.121 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.080 ms/op
Iteration   1: 2.149 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   4.048 ms/op
                 createUser·p0.999:  28.610 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14897
  mean =      2.149 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12617 
    [ 2.500,  5.000) = 2154 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      4.048 ms/op
     p(99.9000) =     28.610 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.081 ms/op
Iteration   1: 1.973 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   3.859 ms/op
                 existUser·p0.999:  10.873 ms/op
                 existUser·p0.9999: 10.961 ms/op
                 existUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16189
  mean =      1.973 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 14291 
    [ 2.500,  3.750) = 1100 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.859 ms/op
     p(99.9000) =     10.873 ms/op
     p(99.9900) =     10.961 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.132 ms/op
Iteration   1: 2.242 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  12.646 ms/op
                 getUser·p0.9999: 13.603 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14362
  mean =      2.242 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 10862 
    [ 2.500,  3.750) = 3099 
    [ 3.750,  5.000) = 170 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =     12.646 ms/op
     p(99.9900) =     13.603 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.154 ms/op
Iteration   1: 3.668 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.200 ms/op
                 listUser·p0.999:  14.452 ms/op
                 listUser·p0.9999: 15.237 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8705
  mean =      3.668 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 684 
    [ 2.500,  3.750) = 4407 
    [ 3.750,  5.000) = 3302 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.200 ms/op
     p(99.9000) =     14.452 ms/op
     p(99.9900) =     15.237 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.430          ops/ms
ClientSimple.existUser                       thrpt         10.635          ops/ms
ClientSimple.getUser                         thrpt         14.277          ops/ms
ClientSimple.listUser                        thrpt          8.286          ops/ms
ClientSimple.createUser                       avgt          2.334           ms/op
ClientSimple.existUser                        avgt          1.836           ms/op
ClientSimple.getUser                          avgt          1.994           ms/op
ClientSimple.listUser                         avgt          3.121           ms/op
ClientSimple.createUser                     sample  14897   2.149 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.705           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.048           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.610           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.000           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.000           ms/op
ClientSimple.existUser                      sample  16189   1.973 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.728           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.859           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.873           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.961           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.961           ms/op
ClientSimple.getUser                        sample  14362   2.242 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.717           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.646           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.603           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.746           ms/op
ClientSimple.listUser                       sample   8705   3.668 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.694           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.633           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.200           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.452           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.237           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.237           ms/op

Benchmark result is saved to 1720116729535.json
