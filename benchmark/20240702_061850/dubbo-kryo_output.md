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
# Warmup Iteration   1: 1.041 ops/ms
Iteration   1: 6.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.527 ops/ms


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
# Warmup Iteration   1: 5.268 ops/ms
Iteration   1: 11.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.953 ops/ms


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
# Warmup Iteration   1: 5.350 ops/ms
Iteration   1: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.877 ops/ms


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
# Warmup Iteration   1: 4.668 ops/ms
Iteration   1: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.614 ops/ms


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.109 ms/op
Iteration   1: 2.283 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.283 ms/op


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.129 ms/op
Iteration   1: 2.145 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.145 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.050 ms/op
Iteration   1: 2.279 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.279 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.084 ms/op
Iteration   1: 3.663 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.663 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.090 ms/op
Iteration   1: 2.243 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.310 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 17.499 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14247
  mean =      2.243 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 10348 
    [ 2.500,  3.750) = 3327 
    [ 3.750,  5.000) = 189 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.499 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 2.906 ±(99.9%) 0.074 ms/op
Iteration   1: 1.892 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 12.989 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16897
  mean =      1.892 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 892 
    [ 1.250,  2.500) = 15159 
    [ 2.500,  3.750) = 738 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     12.989 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.099 ms/op
Iteration   1: 2.087 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.863 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  25.669 ms/op
                 getUser·p0.9999: 26.929 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15317
  mean =      2.087 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13233 
    [ 2.500,  5.000) = 2020 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =     25.669 ms/op
     p(99.9900) =     26.929 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.171 ms/op
Iteration   1: 3.835 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.878 ms/op
                 listUser·p0.999:  20.938 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8342
  mean =      3.835 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 545 
    [ 2.500,  5.000) = 7194 
    [ 5.000,  7.500) = 560 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.878 ms/op
     p(99.9000) =     20.938 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.527          ops/ms
ClientSimple.existUser                       thrpt         11.953          ops/ms
ClientSimple.getUser                         thrpt         10.877          ops/ms
ClientSimple.listUser                        thrpt          8.614          ops/ms
ClientSimple.createUser                       avgt          2.283           ms/op
ClientSimple.existUser                        avgt          2.145           ms/op
ClientSimple.getUser                          avgt          2.279           ms/op
ClientSimple.listUser                         avgt          3.663           ms/op
ClientSimple.createUser                     sample  14247   2.243 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.310           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.236           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.431           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.499           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.596           ms/op
ClientSimple.existUser                      sample  16897   1.892 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.655           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.351           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.911           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.989           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.091           ms/op
ClientSimple.getUser                        sample  15317   2.087 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.477           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.207           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.760           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.669           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.929           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.034           ms/op
ClientSimple.listUser                       sample   8342   3.835 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.075           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.858           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.390           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.878           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.938           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.020           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.020           ms/op

Benchmark result is saved to 1719900865139.json
