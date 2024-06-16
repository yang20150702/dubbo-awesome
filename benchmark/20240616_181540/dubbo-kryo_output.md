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
# Warmup Iteration   1: 1.707 ops/ms
Iteration   1: 6.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.328 ops/ms


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
# Warmup Iteration   1: 5.554 ops/ms
Iteration   1: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.158 ops/ms


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
# Warmup Iteration   1: 5.653 ops/ms
Iteration   1: 12.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.424 ops/ms


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
# Warmup Iteration   1: 4.880 ops/ms
Iteration   1: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.578 ops/ms


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.081 ms/op
Iteration   1: 2.207 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.075 ms/op
Iteration   1: 2.111 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.055 ms/op
Iteration   1: 1.871 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.871 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.086 ms/op
Iteration   1: 3.571 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.571 ms/op


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.091 ms/op
Iteration   1: 2.385 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.875 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  20.074 ms/op
                 createUser·p0.9999: 21.959 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13400
  mean =      2.385 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9204 
    [ 2.500,  5.000) = 3964 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     20.074 ms/op
     p(99.9900) =     21.959 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.097 ms/op
Iteration   1: 2.085 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.118 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   3.195 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 13.748 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15354
  mean =      2.085 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 619 
    [ 1.250,  2.500) = 12432 
    [ 2.500,  3.750) = 2218 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.195 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     13.748 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.078 ms/op
Iteration   1: 2.145 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.013 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  11.798 ms/op
                 getUser·p0.9999: 11.920 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14899
  mean =      2.145 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 11967 
    [ 2.500,  3.750) = 2630 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     11.798 ms/op
     p(99.9900) =     11.920 ms/op
     p(99.9990) =     11.944 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.129 ms/op
Iteration   1: 3.735 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.119 ms/op
                 listUser·p0.999:  7.769 ms/op
                 listUser·p0.9999: 8.126 ms/op
                 listUser·p1.00:   8.126 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8574
  mean =      3.735 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 26 
    [2.000, 2.500) = 335 
    [2.500, 3.000) = 1451 
    [3.000, 3.500) = 1393 
    [3.500, 4.000) = 2539 
    [4.000, 4.500) = 1475 
    [4.500, 5.000) = 718 
    [5.000, 5.500) = 363 
    [5.500, 6.000) = 154 
    [6.000, 6.500) = 50 
    [6.500, 7.000) = 22 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 31 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =      7.769 ms/op
     p(99.9900) =      8.126 ms/op
     p(99.9990) =      8.126 ms/op
     p(99.9999) =      8.126 ms/op
    p(100.0000) =      8.126 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.328          ops/ms
ClientSimple.existUser                       thrpt         11.158          ops/ms
ClientSimple.getUser                         thrpt         12.424          ops/ms
ClientSimple.listUser                        thrpt          7.578          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          2.111           ms/op
ClientSimple.getUser                          avgt          1.871           ms/op
ClientSimple.listUser                         avgt          3.571           ms/op
ClientSimple.createUser                     sample  13400   2.385 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.818           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.201           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.074           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.959           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.282           ms/op
ClientSimple.existUser                      sample  15354   2.085 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.506           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.195           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.255           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.748           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.844           ms/op
ClientSimple.getUser                        sample  14899   2.145 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.013           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.792           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.798           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.920           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.944           ms/op
ClientSimple.listUser                       sample   8574   3.735 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.790           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.153           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.119           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.769           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.126           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.126           ms/op

Benchmark result is saved to 1718561474648.json
