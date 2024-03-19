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
# Warmup Iteration   1: 1.982 ops/ms
Iteration   1: 7.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.412 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.941 ops/ms
Iteration   1: 11.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.914 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.501 ops/ms
Iteration   1: 13.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.687 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.250 ops/ms
Iteration   1: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.732 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ±(99.9%) 0.052 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.454 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.063 ±(99.9%) 0.042 ms/op
Iteration   1: 2.086 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.086 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ±(99.9%) 0.052 ms/op
Iteration   1: 2.041 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.041 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.082 ms/op
Iteration   1: 3.097 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.097 ms/op


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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.108 ms/op
Iteration   1: 2.199 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.900 ms/op
                 createUser·p0.99:   7.548 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 15.251 ms/op
                 createUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14542
  mean =      2.199 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 11609 
    [ 2.500,  3.750) = 2329 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      7.548 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     15.251 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 2.981 ±(99.9%) 0.071 ms/op
Iteration   1: 1.845 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.261 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.170 ms/op
                 existUser·p0.999:  24.598 ms/op
                 existUser·p0.9999: 25.079 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17325
  mean =      1.845 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16789 
    [ 2.500,  5.000) = 420 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.170 ms/op
     p(99.9000) =     24.598 ms/op
     p(99.9900) =     25.079 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 2.914 ±(99.9%) 0.075 ms/op
Iteration   1: 2.027 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.523 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   3.585 ms/op
                 getUser·p0.999:  5.662 ms/op
                 getUser·p0.9999: 5.912 ms/op
                 getUser·p1.00:   5.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15895
  mean =      2.027 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 23 
    [1.000, 1.500) = 925 
    [1.500, 2.000) = 8220 
    [2.000, 2.500) = 5034 
    [2.500, 3.000) = 1247 
    [3.000, 3.500) = 279 
    [3.500, 4.000) = 41 
    [4.000, 4.500) = 33 
    [4.500, 5.000) = 29 
    [5.000, 5.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.585 ms/op
     p(99.9000) =      5.662 ms/op
     p(99.9900) =      5.912 ms/op
     p(99.9990) =      5.956 ms/op
     p(99.9999) =      5.956 ms/op
    p(100.0000) =      5.956 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.115 ms/op
Iteration   1: 3.160 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   4.066 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.773 ms/op
                 listUser·p0.999:  26.014 ms/op
                 listUser·p0.9999: 28.409 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10112
  mean =      3.160 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2505 
    [ 2.500,  5.000) = 7448 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      4.066 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.773 ms/op
     p(99.9000) =     26.014 ms/op
     p(99.9900) =     28.409 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.412          ops/ms
ClientSimple.existUser                       thrpt         11.914          ops/ms
ClientSimple.getUser                         thrpt         13.687          ops/ms
ClientSimple.listUser                        thrpt          9.732          ops/ms
ClientSimple.createUser                       avgt          2.454           ms/op
ClientSimple.existUser                        avgt          2.086           ms/op
ClientSimple.getUser                          avgt          2.041           ms/op
ClientSimple.listUser                         avgt          3.097           ms/op
ClientSimple.createUser                     sample  14542   2.199 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.631           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.548           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.385           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.251           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.385           ms/op
ClientSimple.existUser                      sample  17325   1.845 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.261           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.170           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.598           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.079           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.199           ms/op
ClientSimple.getUser                        sample  15895   2.027 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.784           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.585           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.662           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          5.912           ms/op
ClientSimple.getUser:getUser·p1.00          sample          5.956           ms/op
ClientSimple.listUser                       sample  10112   3.160 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.835           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.066           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.773           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.014           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.409           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.410           ms/op

Benchmark result is saved to 1710828678258.json
