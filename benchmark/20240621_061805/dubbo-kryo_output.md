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
# Warmup Iteration   1: 1.446 ops/ms
Iteration   1: 6.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.282 ops/ms


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
# Warmup Iteration   1: 6.476 ops/ms
Iteration   1: 12.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.414 ops/ms


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
# Warmup Iteration   1: 6.540 ops/ms
Iteration   1: 13.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.325 ops/ms


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
# Warmup Iteration   1: 5.210 ops/ms
Iteration   1: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.447 ops/ms


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.084 ms/op
Iteration   1: 1.996 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.996 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.049 ms/op
Iteration   1: 1.868 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ±(99.9%) 0.059 ms/op
Iteration   1: 1.900 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.900 ms/op


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
# Warmup Iteration   1: 5.366 ±(99.9%) 0.107 ms/op
Iteration   1: 3.075 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.075 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.084 ms/op
Iteration   1: 2.094 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.548 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   4.998 ms/op
                 createUser·p0.999:  25.484 ms/op
                 createUser·p0.9999: 26.845 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15291
  mean =      2.094 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13565 
    [ 2.500,  5.000) = 1574 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.998 ms/op
     p(99.9000) =     25.484 ms/op
     p(99.9900) =     26.845 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.068 ms/op
Iteration   1: 1.872 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.176 ms/op
                 existUser·p0.999:  11.092 ms/op
                 existUser·p0.9999: 11.997 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17162
  mean =      1.872 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 647 
    [ 1.250,  2.500) = 15976 
    [ 2.500,  3.750) = 422 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.176 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     11.997 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.082 ms/op
Iteration   1: 2.328 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.261 ms/op
                 getUser·p0.90:   3.045 ms/op
                 getUser·p0.95:   3.257 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  14.078 ms/op
                 getUser·p0.9999: 14.355 ms/op
                 getUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13735
  mean =      2.328 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 347 
    [ 1.250,  2.500) = 8054 
    [ 2.500,  3.750) = 5124 
    [ 3.750,  5.000) = 167 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      3.045 ms/op
     p(95.0000) =      3.257 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =     14.078 ms/op
     p(99.9900) =     14.355 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.121 ms/op
Iteration   1: 3.126 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.224 ms/op
                 listUser·p0.999:  10.813 ms/op
                 listUser·p0.9999: 11.057 ms/op
                 listUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10219
  mean =      3.126 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 116 
    [ 2.000,  3.000) = 5984 
    [ 3.000,  4.000) = 2694 
    [ 4.000,  5.000) = 1181 
    [ 5.000,  6.000) = 100 
    [ 6.000,  7.000) = 26 
    [ 7.000,  8.000) = 50 
    [ 8.000,  9.000) = 14 
    [ 9.000, 10.000) = 22 
    [10.000, 11.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.224 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     11.057 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.282          ops/ms
ClientSimple.existUser                       thrpt         12.414          ops/ms
ClientSimple.getUser                         thrpt         13.325          ops/ms
ClientSimple.listUser                        thrpt          9.447          ops/ms
ClientSimple.createUser                       avgt          1.996           ms/op
ClientSimple.existUser                        avgt          1.868           ms/op
ClientSimple.getUser                          avgt          1.900           ms/op
ClientSimple.listUser                         avgt          3.075           ms/op
ClientSimple.createUser                     sample  15291   2.094 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.487           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.548           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.998           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.484           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.845           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.001           ms/op
ClientSimple.existUser                      sample  17162   1.872 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.664           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.176           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.092           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.997           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.337           ms/op
ClientSimple.getUser                        sample  13735   2.328 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.045           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.257           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.990           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.078           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.355           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.385           ms/op
ClientSimple.listUser                       sample  10219   3.126 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.161           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.839           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.224           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.813           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.057           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.059           ms/op

Benchmark result is saved to 1718950416213.json
