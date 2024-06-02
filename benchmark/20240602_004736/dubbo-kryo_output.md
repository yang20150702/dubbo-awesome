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
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 6.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.658 ops/ms


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
# Warmup Iteration   1: 6.518 ops/ms
Iteration   1: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.723 ops/ms


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
# Warmup Iteration   1: 5.695 ops/ms
Iteration   1: 13.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.055 ops/ms


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
# Warmup Iteration   1: 5.147 ops/ms
Iteration   1: 8.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.884 ops/ms


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.094 ms/op
Iteration   1: 2.349 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.349 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.045 ms/op
Iteration   1: 1.926 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.056 ms/op
Iteration   1: 1.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.101 ms/op
Iteration   1: 3.408 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.408 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.090 ms/op
Iteration   1: 2.036 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   1.962 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.798 ms/op
                 createUser·p0.99:   3.426 ms/op
                 createUser·p0.999:  33.295 ms/op
                 createUser·p0.9999: 34.787 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15952
  mean =      2.036 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13781 
    [ 2.500,  5.000) = 2139 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
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
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.962 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.426 ms/op
     p(99.9000) =     33.295 ms/op
     p(99.9900) =     34.787 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.077 ms/op
Iteration   1: 2.115 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   2.011 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   5.216 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 13.148 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15127
  mean =      2.115 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 12923 
    [ 2.500,  3.750) = 1788 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      5.216 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     13.148 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.087 ms/op
Iteration   1: 1.965 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.294 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.724 ms/op
                 getUser·p0.999:  12.770 ms/op
                 getUser·p0.9999: 13.162 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16275
  mean =      1.965 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 14650 
    [ 2.500,  3.750) = 1126 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.724 ms/op
     p(99.9000) =     12.770 ms/op
     p(99.9900) =     13.162 ms/op
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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.129 ms/op
Iteration   1: 3.544 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.523 ms/op
                 listUser·p0.999:  10.052 ms/op
                 listUser·p0.9999: 12.698 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9083
  mean =      3.544 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 373 
    [ 2.500,  3.750) = 4957 
    [ 3.750,  5.000) = 3519 
    [ 5.000,  6.250) = 183 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.523 ms/op
     p(99.9000) =     10.052 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.658          ops/ms
ClientSimple.existUser                       thrpt         12.723          ops/ms
ClientSimple.getUser                         thrpt         13.055          ops/ms
ClientSimple.listUser                        thrpt          8.884          ops/ms
ClientSimple.createUser                       avgt          2.349           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.408           ms/op
ClientSimple.createUser                     sample  15952   2.036 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.530           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.962           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.426           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.295           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.787           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.865           ms/op
ClientSimple.existUser                      sample  15127   2.115 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.418           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.011           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.216           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.730           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.148           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.156           ms/op
ClientSimple.getUser                        sample  16275   1.965 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.294           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.724           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.770           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.162           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9083   3.544 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.462           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.523           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.052           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.698           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.698           ms/op

Benchmark result is saved to 1717288999549.json
