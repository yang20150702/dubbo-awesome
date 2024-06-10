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
# Warmup Iteration   1: 1.461 ops/ms
Iteration   1: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.751 ops/ms


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
# Warmup Iteration   1: 7.095 ops/ms
Iteration   1: 13.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.562 ops/ms


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
# Warmup Iteration   1: 6.532 ops/ms
Iteration   1: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.626 ops/ms


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
# Warmup Iteration   1: 4.452 ops/ms
Iteration   1: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.071 ops/ms


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.058 ms/op
Iteration   1: 2.254 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.254 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.059 ms/op
Iteration   1: 2.124 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ±(99.9%) 0.061 ms/op
Iteration   1: 1.868 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.868 ms/op


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
# Warmup Iteration   1: 4.894 ±(99.9%) 0.104 ms/op
Iteration   1: 3.085 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.085 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.102 ms/op
Iteration   1: 2.055 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.399 ms/op
                 createUser·p0.95:   2.675 ms/op
                 createUser·p0.99:   5.416 ms/op
                 createUser·p0.999:  18.004 ms/op
                 createUser·p0.9999: 18.954 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15561
  mean =      2.055 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 14294 
    [ 2.500,  3.750) = 928 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.399 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      5.416 ms/op
     p(99.9000) =     18.004 ms/op
     p(99.9900) =     18.954 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 2.700 ±(99.9%) 0.067 ms/op
Iteration   1: 1.941 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.345 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.444 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   4.213 ms/op
                 existUser·p0.999:  25.888 ms/op
                 existUser·p0.9999: 26.577 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16473
  mean =      1.941 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15153 
    [ 2.500,  5.000) = 1166 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.444 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.213 ms/op
     p(99.9000) =     25.888 ms/op
     p(99.9900) =     26.577 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.091 ms/op
Iteration   1: 1.998 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   4.241 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 12.029 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15980
  mean =      1.998 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 14242 
    [ 2.500,  3.750) = 1198 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.241 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     12.029 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.145 ms/op
Iteration   1: 3.313 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.084 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   5.853 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9674
  mean =      3.313 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1750 
    [ 2.500,  5.000) = 7578 
    [ 5.000,  7.500) = 282 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.853 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.751          ops/ms
ClientSimple.existUser                       thrpt         13.562          ops/ms
ClientSimple.getUser                         thrpt         12.626          ops/ms
ClientSimple.listUser                        thrpt          9.071          ops/ms
ClientSimple.createUser                       avgt          2.254           ms/op
ClientSimple.existUser                        avgt          2.124           ms/op
ClientSimple.getUser                          avgt          1.868           ms/op
ClientSimple.listUser                         avgt          3.085           ms/op
ClientSimple.createUser                     sample  15561   2.055 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.656           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.399           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.416           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.004           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.954           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.973           ms/op
ClientSimple.existUser                      sample  16473   1.941 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.345           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.444           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.213           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.888           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.577           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.640           ms/op
ClientSimple.getUser                        sample  15980   1.998 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.725           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.241           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.370           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.029           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.059           ms/op
ClientSimple.listUser                       sample   9674   3.313 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.964           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.084           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.853           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.266           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.529           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.529           ms/op

Benchmark result is saved to 1717980136948.json
