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
# Warmup Iteration   1: 1.643 ops/ms
Iteration   1: 6.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.727 ops/ms


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
# Warmup Iteration   1: 6.099 ops/ms
Iteration   1: 11.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.511 ops/ms


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
# Warmup Iteration   1: 4.295 ops/ms
Iteration   1: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.537 ops/ms


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
# Warmup Iteration   1: 5.177 ops/ms
Iteration   1: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.972 ops/ms


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.066 ms/op
Iteration   1: 2.394 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.394 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.053 ms/op
Iteration   1: 1.979 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.979 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.054 ms/op
Iteration   1: 1.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.988 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.093 ms/op
Iteration   1: 3.087 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.087 ms/op


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.089 ms/op
Iteration   1: 2.396 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.208 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  16.034 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13333
  mean =      2.396 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 9058 
    [ 2.500,  3.750) = 3999 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.208 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     16.034 ms/op
     p(99.9900) =     16.253 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.059 ms/op
Iteration   1: 1.696 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   1.989 ms/op
                 existUser·p0.95:   2.195 ms/op
                 existUser·p0.99:   2.707 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 6.387 ms/op
                 existUser·p1.00:   6.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18856
  mean =      1.696 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 80 
    [1.000, 1.500) = 3716 
    [1.500, 2.000) = 13263 
    [2.000, 2.500) = 1458 
    [2.500, 3.000) = 213 
    [3.000, 3.500) = 66 
    [3.500, 4.000) = 3 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      1.989 ms/op
     p(95.0000) =      2.195 ms/op
     p(99.0000) =      2.707 ms/op
     p(99.9000) =      5.939 ms/op
     p(99.9900) =      6.387 ms/op
     p(99.9990) =      6.431 ms/op
     p(99.9999) =      6.431 ms/op
    p(100.0000) =      6.431 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.109 ms/op
Iteration   1: 2.072 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   4.218 ms/op
                 getUser·p0.999:  27.646 ms/op
                 getUser·p0.9999: 28.291 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15436
  mean =      2.072 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13947 
    [ 2.500,  5.000) = 1377 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      4.218 ms/op
     p(99.9000) =     27.646 ms/op
     p(99.9900) =     28.291 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.113 ms/op
Iteration   1: 3.555 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.383 ms/op
                 listUser·p0.999:  23.986 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8993
  mean =      3.555 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1481 
    [ 2.500,  5.000) = 7201 
    [ 5.000,  7.500) = 275 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.383 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.727          ops/ms
ClientSimple.existUser                       thrpt         11.511          ops/ms
ClientSimple.getUser                         thrpt         12.537          ops/ms
ClientSimple.listUser                        thrpt          7.972          ops/ms
ClientSimple.createUser                       avgt          2.394           ms/op
ClientSimple.existUser                        avgt          1.979           ms/op
ClientSimple.getUser                          avgt          1.988           ms/op
ClientSimple.listUser                         avgt          3.087           ms/op
ClientSimple.createUser                     sample  13333   2.396 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.790           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.208           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.382           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.034           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.253           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.269           ms/op
ClientSimple.existUser                      sample  18856   1.696 ± 0.008   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.989           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.939           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.387           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.431           ms/op
ClientSimple.getUser                        sample  15436   2.072 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.218           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.646           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.291           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.344           ms/op
ClientSimple.listUser                       sample   8993   3.555 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.200           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.383           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.986           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.183           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.183           ms/op

Benchmark result is saved to 1720744904883.json
