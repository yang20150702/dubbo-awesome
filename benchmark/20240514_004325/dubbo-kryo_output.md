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
# Warmup Iteration   1: 2.333 ops/ms
Iteration   1: 7.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.489 ops/ms


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
# Warmup Iteration   1: 5.805 ops/ms
Iteration   1: 14.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.250 ops/ms


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
# Warmup Iteration   1: 5.749 ops/ms
Iteration   1: 13.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.423 ops/ms


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
# Warmup Iteration   1: 5.058 ops/ms
Iteration   1: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.493 ops/ms


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.067 ms/op
Iteration   1: 2.098 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.098 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.055 ms/op
Iteration   1: 1.820 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.820 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.053 ms/op
Iteration   1: 1.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.991 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.087 ms/op
Iteration   1: 3.453 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.453 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.094 ms/op
Iteration   1: 2.195 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.266 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   8.285 ms/op
                 createUser·p0.999:  21.529 ms/op
                 createUser·p0.9999: 21.972 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14561
  mean =      2.195 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11230 
    [ 2.500,  5.000) = 3120 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      8.285 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     21.972 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 2.884 ±(99.9%) 0.070 ms/op
Iteration   1: 1.783 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.258 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.422 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 12.305 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18227
  mean =      1.783 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 980 
    [ 1.250,  2.500) = 16516 
    [ 2.500,  3.750) = 581 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.258 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.422 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     12.305 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.079 ms/op
Iteration   1: 1.962 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.056 ms/op
                 getUser·p0.999:  12.884 ms/op
                 getUser·p0.9999: 13.131 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16296
  mean =      1.962 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 14585 
    [ 2.500,  3.750) = 1377 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.056 ms/op
     p(99.9000) =     12.884 ms/op
     p(99.9900) =     13.131 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.153 ms/op
Iteration   1: 3.457 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.445 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.004 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9241
  mean =      3.457 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 1022 
    [ 2.500,  3.750) = 4836 
    [ 3.750,  5.000) = 3129 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.004 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     16.712 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.489          ops/ms
ClientSimple.existUser                       thrpt         14.250          ops/ms
ClientSimple.getUser                         thrpt         13.423          ops/ms
ClientSimple.listUser                        thrpt          8.493          ops/ms
ClientSimple.createUser                       avgt          2.098           ms/op
ClientSimple.existUser                        avgt          1.820           ms/op
ClientSimple.getUser                          avgt          1.991           ms/op
ClientSimple.listUser                         avgt          3.453           ms/op
ClientSimple.createUser                     sample  14561   2.195 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.266           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.285           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.529           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.972           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.987           ms/op
ClientSimple.existUser                      sample  18227   1.783 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.640           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.258           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.422           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.616           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.305           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.386           ms/op
ClientSimple.getUser                        sample  16296   1.962 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.884           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.131           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9241   3.457 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.002           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.445           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.004           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.958           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.712           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.712           ms/op

Benchmark result is saved to 1715647144552.json
