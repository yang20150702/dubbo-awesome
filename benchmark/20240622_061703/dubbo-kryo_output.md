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
# Warmup Iteration   1: 1.505 ops/ms
Iteration   1: 6.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.183 ops/ms


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
# Warmup Iteration   1: 6.485 ops/ms
Iteration   1: 11.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.872 ops/ms


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
# Warmup Iteration   1: 5.649 ops/ms
Iteration   1: 12.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.212 ops/ms


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
# Warmup Iteration   1: 4.685 ops/ms
Iteration   1: 8.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.281 ops/ms


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.060 ms/op
Iteration   1: 2.138 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.067 ms/op
Iteration   1: 2.117 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.117 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.052 ms/op
Iteration   1: 2.049 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.049 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.071 ms/op
Iteration   1: 3.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.172 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.102 ms/op
Iteration   1: 2.307 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  40.528 ms/op
                 createUser·p0.9999: 57.711 ms/op
                 createUser·p1.00:   59.965 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13865
  mean =      2.307 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13591 
    [ 5.000, 10.000) = 126 
    [10.000, 15.000) = 82 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 27 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     40.528 ms/op
     p(99.9900) =     57.711 ms/op
     p(99.9990) =     59.965 ms/op
     p(99.9999) =     59.965 ms/op
    p(100.0000) =     59.965 ms/op


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
# Warmup Iteration   1: 2.951 ±(99.9%) 0.068 ms/op
Iteration   1: 2.045 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.011 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.220 ms/op
                 existUser·p0.999:  15.038 ms/op
                 existUser·p0.9999: 15.797 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15797
  mean =      2.045 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 13975 
    [ 2.500,  3.750) = 1325 
    [ 3.750,  5.000) = 6 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.220 ms/op
     p(99.9000) =     15.038 ms/op
     p(99.9900) =     15.797 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.113 ms/op
Iteration   1: 2.041 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.415 ms/op
                 getUser·p0.50:   1.837 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   3.369 ms/op
                 getUser·p0.999:  15.813 ms/op
                 getUser·p0.9999: 16.944 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15843
  mean =      2.041 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 12448 
    [ 2.500,  3.750) = 3109 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      3.369 ms/op
     p(99.9000) =     15.813 ms/op
     p(99.9900) =     16.944 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.134 ms/op
Iteration   1: 3.639 ±(99.9%) 0.067 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   14.123 ms/op
                 listUser·p0.999:  25.795 ms/op
                 listUser·p0.9999: 27.034 ms/op
                 listUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8790
  mean =      3.639 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 700 
    [ 2.500,  5.000) = 7828 
    [ 5.000,  7.500) = 134 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =     14.123 ms/op
     p(99.9000) =     25.795 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.183          ops/ms
ClientSimple.existUser                       thrpt         11.872          ops/ms
ClientSimple.getUser                         thrpt         12.212          ops/ms
ClientSimple.listUser                        thrpt          8.281          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          2.117           ms/op
ClientSimple.getUser                          avgt          2.049           ms/op
ClientSimple.listUser                         avgt          3.172           ms/op
ClientSimple.createUser                     sample  13865   2.307 ± 0.069   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.472           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.109           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.528           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         57.711           ms/op
ClientSimple.createUser:createUser·p1.00    sample         59.965           ms/op
ClientSimple.existUser                      sample  15797   2.045 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.592           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.011           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.220           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.038           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.797           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  15843   2.041 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.415           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.837           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.369           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.944           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.039           ms/op
ClientSimple.listUser                       sample   8790   3.639 ± 0.067   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.137           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.123           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.795           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.034           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.034           ms/op

Benchmark result is saved to 1719036767259.json
