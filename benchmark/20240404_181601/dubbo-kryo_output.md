# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.401 ops/ms
Iteration   1: 6.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.432 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ops/ms
Iteration   1: 11.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.652 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.168 ops/ms
Iteration   1: 11.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.616 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.035 ops/ms
Iteration   1: 7.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.569 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ±(99.9%) 0.076 ms/op
Iteration   1: 2.157 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.212 ±(99.9%) 0.047 ms/op
Iteration   1: 1.875 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.316 ±(99.9%) 0.054 ms/op
Iteration   1: 1.935 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.765 ±(99.9%) 0.102 ms/op
Iteration   1: 3.625 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.523 ±(99.9%) 0.089 ms/op
Iteration   1: 2.148 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.490 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 18.630 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14909
  mean =      2.148 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 291 
    [ 1.250,  2.500) = 13166 
    [ 2.500,  3.750) = 1011 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     18.630 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.432 ±(99.9%) 0.097 ms/op
Iteration   1: 2.183 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.232 ms/op
                 existUser·p0.50:   2.083 ms/op
                 existUser·p0.90:   2.802 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  23.258 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14709
  mean =      2.183 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11305 
    [ 2.500,  5.000) = 3234 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.232 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     23.258 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ±(99.9%) 0.078 ms/op
Iteration   1: 1.928 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   1.784 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   3.126 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16619
  mean =      1.928 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15739 
    [ 2.500,  5.000) = 810 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.126 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.485 ±(99.9%) 0.124 ms/op
Iteration   1: 3.402 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.348 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 9.339 ms/op
                 listUser·p1.00:   9.339 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9404
  mean =      3.402 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 6 
    [ 1.000,  2.000) = 153 
    [ 2.000,  3.000) = 3087 
    [ 3.000,  4.000) = 4288 
    [ 4.000,  5.000) = 1543 
    [ 5.000,  6.000) = 213 
    [ 6.000,  7.000) = 50 
    [ 7.000,  8.000) = 42 
    [ 8.000,  9.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.348 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =      9.339 ms/op
     p(99.9990) =      9.339 ms/op
     p(99.9999) =      9.339 ms/op
    p(100.0000) =      9.339 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.432          ops/ms
ClientSimple.existUser                       thrpt         11.652          ops/ms
ClientSimple.getUser                         thrpt         11.616          ops/ms
ClientSimple.listUser                        thrpt          7.569          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.625           ms/op
ClientSimple.createUser                     sample  14909   2.148 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.490           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.946           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.793           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.630           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.711           ms/op
ClientSimple.existUser                      sample  14709   2.183 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.232           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.128           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.258           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.247           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.247           ms/op
ClientSimple.getUser                        sample  16619   1.928 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.707           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.784           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.126           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.168           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.332           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.332           ms/op
ClientSimple.listUser                       sample   9404   3.402 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.579           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.348           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.864           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.339           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.339           ms/op

Benchmark result is saved to 1712254296528.json
