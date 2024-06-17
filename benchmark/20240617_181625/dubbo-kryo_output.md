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
# Warmup Iteration   1: 0.729 ops/ms
Iteration   1: 6.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.139 ops/ms


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
# Warmup Iteration   1: 5.670 ops/ms
Iteration   1: 13.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.617 ops/ms


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
# Warmup Iteration   1: 5.522 ops/ms
Iteration   1: 14.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.645 ops/ms


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
# Warmup Iteration   1: 5.168 ops/ms
Iteration   1: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.531 ops/ms


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.094 ms/op
Iteration   1: 2.195 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.195 ms/op


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
# Warmup Iteration   1: 2.982 ±(99.9%) 0.046 ms/op
Iteration   1: 1.899 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.899 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.077 ms/op
Iteration   1: 2.124 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.124 ms/op


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.087 ms/op
Iteration   1: 3.478 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.478 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.089 ms/op
Iteration   1: 2.258 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   8.750 ms/op
                 createUser·p0.999:  19.699 ms/op
                 createUser·p0.9999: 20.171 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14163
  mean =      2.258 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11438 
    [ 2.500,  5.000) = 2498 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      8.750 ms/op
     p(99.9000) =     19.699 ms/op
     p(99.9900) =     20.171 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.069 ms/op
Iteration   1: 2.088 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.991 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.785 ms/op
                 existUser·p0.99:   3.627 ms/op
                 existUser·p0.999:  14.544 ms/op
                 existUser·p0.9999: 14.843 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15309
  mean =      2.088 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 13066 
    [ 2.500,  3.750) = 1891 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.627 ms/op
     p(99.9000) =     14.544 ms/op
     p(99.9900) =     14.843 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.077 ms/op
Iteration   1: 1.959 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.457 ms/op
                 getUser·p0.50:   1.829 ms/op
                 getUser·p0.90:   2.359 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   5.132 ms/op
                 getUser·p0.999:  15.860 ms/op
                 getUser·p0.9999: 16.411 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16328
  mean =      1.959 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 294 
    [ 1.250,  2.500) = 15028 
    [ 2.500,  3.750) = 735 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      5.132 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     16.411 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.220 ms/op
Iteration   1: 3.586 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.541 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  11.159 ms/op
                 listUser·p0.9999: 12.452 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8913
  mean =      3.586 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 465 
    [ 2.500,  3.750) = 5069 
    [ 3.750,  5.000) = 3134 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.541 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     11.159 ms/op
     p(99.9900) =     12.452 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.139          ops/ms
ClientSimple.existUser                       thrpt         13.617          ops/ms
ClientSimple.getUser                         thrpt         14.645          ops/ms
ClientSimple.listUser                        thrpt          8.531          ops/ms
ClientSimple.createUser                       avgt          2.195           ms/op
ClientSimple.existUser                        avgt          1.899           ms/op
ClientSimple.getUser                          avgt          2.124           ms/op
ClientSimple.listUser                         avgt          3.478           ms/op
ClientSimple.createUser                     sample  14163   2.258 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.618           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.060           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.750           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.699           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.171           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.185           ms/op
ClientSimple.existUser                      sample  15309   2.088 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.518           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.991           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.627           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.544           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.843           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.860           ms/op
ClientSimple.getUser                        sample  16328   1.959 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.457           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.829           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.132           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.860           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.411           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.515           ms/op
ClientSimple.listUser                       sample   8913   3.586 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.741           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.541           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.455           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.159           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.452           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.452           ms/op

Benchmark result is saved to 1718647948133.json
