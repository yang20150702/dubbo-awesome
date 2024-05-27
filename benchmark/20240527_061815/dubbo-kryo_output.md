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
# Warmup Iteration   1: 1.839 ops/ms
Iteration   1: 6.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.742 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.949 ops/ms
Iteration   1: 12.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.842 ops/ms


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
# Warmup Iteration   1: 6.014 ops/ms
Iteration   1: 13.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.355 ops/ms


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
# Warmup Iteration   1: 4.590 ops/ms
Iteration   1: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.587 ops/ms


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.066 ms/op
Iteration   1: 2.443 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.443 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.058 ms/op
Iteration   1: 1.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.958 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.058 ms/op
Iteration   1: 1.968 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.968 ms/op


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.084 ms/op
Iteration   1: 3.514 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.514 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.097 ms/op
Iteration   1: 2.346 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   2.286 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   7.456 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 21.787 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13682
  mean =      2.346 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9858 
    [ 2.500,  5.000) = 3626 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      7.456 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     21.787 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.064 ms/op
Iteration   1: 2.066 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.987 ms/op
                 existUser·p0.90:   2.467 ms/op
                 existUser·p0.95:   2.785 ms/op
                 existUser·p0.99:   4.093 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 15.219 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15477
  mean =      2.066 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 235 
    [ 1.250,  2.500) = 13881 
    [ 2.500,  3.750) = 1171 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.467 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.093 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     15.219 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.098 ms/op
Iteration   1: 2.217 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.917 ms/op
                 getUser·p0.99:   3.771 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 12.241 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14415
  mean =      2.217 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 10989 
    [ 2.500,  3.750) = 3186 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.917 ms/op
     p(99.0000) =      3.771 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     12.241 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 6.625 ±(99.9%) 0.203 ms/op
Iteration   1: 3.675 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   6.581 ms/op
                 listUser·p0.999:  12.866 ms/op
                 listUser·p0.9999: 15.008 ms/op
                 listUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8731
  mean =      3.675 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 563 
    [ 2.500,  3.750) = 4194 
    [ 3.750,  5.000) = 3497 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.581 ms/op
     p(99.9000) =     12.866 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.742          ops/ms
ClientSimple.existUser                       thrpt         12.842          ops/ms
ClientSimple.getUser                         thrpt         13.355          ops/ms
ClientSimple.listUser                        thrpt          8.587          ops/ms
ClientSimple.createUser                       avgt          2.443           ms/op
ClientSimple.existUser                        avgt          1.958           ms/op
ClientSimple.getUser                          avgt          1.968           ms/op
ClientSimple.listUser                         avgt          3.514           ms/op
ClientSimple.createUser                     sample  13682   2.346 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.598           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.456           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.660           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.787           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.823           ms/op
ClientSimple.existUser                      sample  15477   2.066 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.673           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.467           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.093           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.073           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.219           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.237           ms/op
ClientSimple.getUser                        sample  14415   2.217 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.535           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.917           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.771           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.026           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.241           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.255           ms/op
ClientSimple.listUser                       sample   8731   3.675 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.041           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.030           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.581           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.866           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.008           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.008           ms/op

Benchmark result is saved to 1716790425656.json
