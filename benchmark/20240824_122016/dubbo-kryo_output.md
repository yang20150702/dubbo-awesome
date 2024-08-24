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
# Warmup Iteration   1: 1.537 ops/ms
Iteration   1: 6.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.253 ops/ms


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
# Warmup Iteration   1: 6.080 ops/ms
Iteration   1: 12.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.256 ops/ms


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
# Warmup Iteration   1: 6.663 ops/ms
Iteration   1: 12.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.088 ops/ms


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
# Warmup Iteration   1: 4.560 ops/ms
Iteration   1: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.563 ops/ms


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.066 ms/op
Iteration   1: 2.241 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.049 ms/op
Iteration   1: 1.904 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.067 ms/op
Iteration   1: 2.034 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.093 ms/op
Iteration   1: 3.393 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.393 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.086 ms/op
Iteration   1: 2.085 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  14.893 ms/op
                 createUser·p0.9999: 15.575 ms/op
                 createUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15327
  mean =      2.085 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 12885 
    [ 2.500,  3.750) = 2081 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     15.575 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 2.997 ±(99.9%) 0.065 ms/op
Iteration   1: 1.837 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.220 ms/op
                 existUser·p0.999:  15.532 ms/op
                 existUser·p0.9999: 15.700 ms/op
                 existUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17478
  mean =      1.837 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1826 
    [ 1.250,  2.500) = 14280 
    [ 2.500,  3.750) = 1258 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.220 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     15.700 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.104 ms/op
Iteration   1: 1.930 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   1.718 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 12.989 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16569
  mean =      1.930 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 14791 
    [ 2.500,  3.750) = 1203 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     12.989 ms/op
     p(99.9990) =     13.107 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.127 ms/op
Iteration   1: 3.749 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.403 ms/op
                 listUser·p0.999:  26.230 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8533
  mean =      3.749 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 566 
    [ 2.500,  5.000) = 7629 
    [ 5.000,  7.500) = 259 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.403 ms/op
     p(99.9000) =     26.230 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.253          ops/ms
ClientSimple.existUser                       thrpt         12.256          ops/ms
ClientSimple.getUser                         thrpt         12.088          ops/ms
ClientSimple.listUser                        thrpt          8.563          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.393           ms/op
ClientSimple.createUser                     sample  15327   2.085 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.893           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.575           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.942           ms/op
ClientSimple.existUser                      sample  17478   1.837 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.690           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.220           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.532           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.700           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.712           ms/op
ClientSimple.getUser                        sample  16569   1.930 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.718           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.448           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.059           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.989           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.107           ms/op
ClientSimple.listUser                       sample   8533   3.749 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.839           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.403           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.230           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.706           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.706           ms/op

Benchmark result is saved to 1724501755697.json
