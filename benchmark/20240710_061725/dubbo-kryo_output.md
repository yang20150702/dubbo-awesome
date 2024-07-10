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
# Warmup Iteration   1: 1.705 ops/ms
Iteration   1: 6.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.250 ops/ms


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
# Warmup Iteration   1: 5.314 ops/ms
Iteration   1: 12.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.326 ops/ms


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
# Warmup Iteration   1: 5.494 ops/ms
Iteration   1: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.408 ops/ms


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
# Warmup Iteration   1: 4.500 ops/ms
Iteration   1: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.007 ops/ms


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.053 ms/op
Iteration   1: 2.053 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.053 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.046 ms/op
Iteration   1: 1.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


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
# Warmup Iteration   1: 3.412 ±(99.9%) 0.068 ms/op
Iteration   1: 2.022 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.022 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.111 ms/op
Iteration   1: 3.536 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.536 ms/op


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.086 ms/op
Iteration   1: 2.271 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  15.203 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14070
  mean =      2.271 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 10814 
    [ 2.500,  3.750) = 2544 
    [ 3.750,  5.000) = 159 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     15.203 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.148 ±(99.9%) 0.086 ms/op
Iteration   1: 1.821 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 16.120 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17549
  mean =      1.821 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 592 
    [ 1.250,  2.500) = 16199 
    [ 2.500,  3.750) = 573 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     16.120 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.075 ms/op
Iteration   1: 2.220 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.134 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.908 ms/op
                 getUser·p0.99:   4.094 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 11.629 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14405
  mean =      2.220 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 10978 
    [ 2.500,  3.750) = 3179 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      4.094 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     11.629 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.116 ms/op
Iteration   1: 3.419 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.240 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.287 ms/op
                 listUser·p0.999:  22.608 ms/op
                 listUser·p0.9999: 28.606 ms/op
                 listUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9354
  mean =      3.419 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 432 
    [ 2.500,  5.000) = 8725 
    [ 5.000,  7.500) = 153 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.287 ms/op
     p(99.9000) =     22.608 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.250          ops/ms
ClientSimple.existUser                       thrpt         12.326          ops/ms
ClientSimple.getUser                         thrpt         10.408          ops/ms
ClientSimple.listUser                        thrpt          9.007          ops/ms
ClientSimple.createUser                       avgt          2.053           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          2.022           ms/op
ClientSimple.listUser                         avgt          3.536           ms/op
ClientSimple.createUser                     sample  14070   2.271 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.630           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.595           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.089           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.089           ms/op
ClientSimple.existUser                      sample  17549   1.821 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.965           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.155           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.120           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.368           ms/op
ClientSimple.getUser                        sample  14405   2.220 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.667           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.094           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.436           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.629           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.665           ms/op
ClientSimple.listUser                       sample   9354   3.419 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.240           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.287           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.608           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.606           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.606           ms/op

Benchmark result is saved to 1720591989900.json
