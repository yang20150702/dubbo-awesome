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
# Warmup Iteration   1: 1.816 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.246 ops/ms
Iteration   1: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.668 ops/ms


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
# Warmup Iteration   1: 5.832 ops/ms
Iteration   1: 13.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.979 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.213 ops/ms
Iteration   1: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.752 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.065 ms/op
Iteration   1: 2.164 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ±(99.9%) 0.051 ms/op
Iteration   1: 1.858 ±(99.9%) 0.009 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.094 ms/op
Iteration   1: 2.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.068 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.077 ms/op
Iteration   1: 3.049 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.049 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.089 ms/op
Iteration   1: 2.218 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   2.848 ms/op
                 createUser·p0.99:   4.564 ms/op
                 createUser·p0.999:  21.942 ms/op
                 createUser·p0.9999: 23.451 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14693
  mean =      2.218 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12256 
    [ 2.500,  5.000) = 2317 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.848 ms/op
     p(99.0000) =      4.564 ms/op
     p(99.9000) =     21.942 ms/op
     p(99.9900) =     23.451 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.115 ±(99.9%) 0.069 ms/op
Iteration   1: 1.941 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   2.967 ms/op
                 existUser·p0.999:  33.620 ms/op
                 existUser·p0.9999: 34.059 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16469
  mean =      1.941 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15420 
    [ 2.500,  5.000) = 970 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      2.967 ms/op
     p(99.9000) =     33.620 ms/op
     p(99.9900) =     34.059 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.078 ms/op
Iteration   1: 2.125 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.431 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   3.019 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  25.657 ms/op
                 getUser·p0.9999: 26.885 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15388
  mean =      2.125 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12156 
    [ 2.500,  5.000) = 3181 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     26.885 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.152 ms/op
Iteration   1: 3.636 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.168 ms/op
                 listUser·p0.999:  25.572 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8801
  mean =      3.636 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 806 
    [ 2.500,  5.000) = 7793 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.168 ms/op
     p(99.9000) =     25.572 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.742          ops/ms
ClientSimple.existUser                       thrpt         12.668          ops/ms
ClientSimple.getUser                         thrpt         13.979          ops/ms
ClientSimple.listUser                        thrpt          8.752          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          1.858           ms/op
ClientSimple.getUser                          avgt          2.068           ms/op
ClientSimple.listUser                         avgt          3.049           ms/op
ClientSimple.createUser                     sample  14693   2.218 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.499           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.848           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.564           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.942           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.451           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.790           ms/op
ClientSimple.existUser                      sample  16469   1.941 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.609           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.967           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.620           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.059           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.144           ms/op
ClientSimple.getUser                        sample  15388   2.125 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.431           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.019           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.572           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.657           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.885           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.903           ms/op
ClientSimple.listUser                       sample   8801   3.636 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.939           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.645           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.168           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.572           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.066           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.066           ms/op

Benchmark result is saved to 1718885800714.json
