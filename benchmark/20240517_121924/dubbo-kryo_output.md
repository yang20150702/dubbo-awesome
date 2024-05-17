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
# Warmup Iteration   1: 1.034 ops/ms
Iteration   1: 6.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.515 ops/ms


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
# Warmup Iteration   1: 5.963 ops/ms
Iteration   1: 12.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.049 ops/ms


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
# Warmup Iteration   1: 5.374 ops/ms
Iteration   1: 13.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.450 ops/ms


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
# Warmup Iteration   1: 5.716 ops/ms
Iteration   1: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.911 ops/ms


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.081 ms/op
Iteration   1: 2.186 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.186 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.049 ms/op
Iteration   1: 1.869 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.049 ms/op
Iteration   1: 2.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.066 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.089 ms/op
Iteration   1: 3.351 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.351 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.082 ms/op
Iteration   1: 2.273 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   7.224 ms/op
                 createUser·p0.999:  40.108 ms/op
                 createUser·p0.9999: 40.408 ms/op
                 createUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14281
  mean =      2.273 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14069 
    [ 5.000, 10.000) = 85 
    [10.000, 15.000) = 58 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      7.224 ms/op
     p(99.9000) =     40.108 ms/op
     p(99.9900) =     40.408 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 3.222 ±(99.9%) 0.078 ms/op
Iteration   1: 2.043 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.956 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.183 ms/op
                 existUser·p0.999:  17.793 ms/op
                 existUser·p0.9999: 18.128 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15875
  mean =      2.043 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 15092 
    [ 2.500,  3.750) = 537 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.183 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     18.128 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.450 ±(99.9%) 0.077 ms/op
Iteration   1: 2.305 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.219 ms/op
                 getUser·p0.50:   2.249 ms/op
                 getUser·p0.90:   2.810 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   3.705 ms/op
                 getUser·p0.999:  30.638 ms/op
                 getUser·p0.9999: 30.900 ms/op
                 getUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13943
  mean =      2.305 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10015 
    [ 2.500,  5.000) = 3851 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.219 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.705 ms/op
     p(99.9000) =     30.638 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.108 ms/op
Iteration   1: 3.400 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  6.315 ms/op
                 listUser·p0.9999: 6.570 ms/op
                 listUser·p1.00:   6.570 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9390
  mean =      3.400 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 67 
    [2.000, 2.500) = 487 
    [2.500, 3.000) = 2849 
    [3.000, 3.500) = 1920 
    [3.500, 4.000) = 2198 
    [4.000, 4.500) = 1182 
    [4.500, 5.000) = 418 
    [5.000, 5.500) = 161 
    [5.500, 6.000) = 68 
    [6.000, 6.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      6.315 ms/op
     p(99.9900) =      6.570 ms/op
     p(99.9990) =      6.570 ms/op
     p(99.9999) =      6.570 ms/op
    p(100.0000) =      6.570 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.515          ops/ms
ClientSimple.existUser                       thrpt         12.049          ops/ms
ClientSimple.getUser                         thrpt         13.450          ops/ms
ClientSimple.listUser                        thrpt          7.911          ops/ms
ClientSimple.createUser                       avgt          2.186           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.066           ms/op
ClientSimple.listUser                         avgt          3.351           ms/op
ClientSimple.createUser                     sample  14281   2.273 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.636           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.224           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.108           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         40.408           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.436           ms/op
ClientSimple.existUser                      sample  15875   2.043 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.956           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.183           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.793           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.128           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.186           ms/op
ClientSimple.getUser                        sample  13943   2.305 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.219           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.249           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.705           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.638           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.900           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.900           ms/op
ClientSimple.listUser                       sample   9390   3.400 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.511           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.579           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.570           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.570           ms/op

Benchmark result is saved to 1715948114168.json
