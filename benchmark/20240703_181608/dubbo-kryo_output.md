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
# Warmup Iteration   1: 1.030 ops/ms
Iteration   1: 6.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.188 ops/ms


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
# Warmup Iteration   1: 6.182 ops/ms
Iteration   1: 11.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.919 ops/ms


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
# Warmup Iteration   1: 5.136 ops/ms
Iteration   1: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.779 ops/ms


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
# Warmup Iteration   1: 4.950 ops/ms
Iteration   1: 8.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.898 ops/ms


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.083 ms/op
Iteration   1: 2.122 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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
# Warmup Iteration   1: 2.944 ±(99.9%) 0.052 ms/op
Iteration   1: 1.798 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.798 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.077 ms/op
Iteration   1: 1.975 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.975 ms/op


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.095 ms/op
Iteration   1: 3.549 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.549 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.104 ms/op
Iteration   1: 2.347 ±(99.9%) 0.070 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   3.083 ms/op
                 createUser·p0.99:   11.578 ms/op
                 createUser·p0.999:  44.040 ms/op
                 createUser·p0.9999: 48.963 ms/op
                 createUser·p1.00:   49.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13621
  mean =      2.347 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13210 
    [ 5.000, 10.000) = 235 
    [10.000, 15.000) = 108 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 26 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      3.083 ms/op
     p(99.0000) =     11.578 ms/op
     p(99.9000) =     44.040 ms/op
     p(99.9900) =     48.963 ms/op
     p(99.9990) =     49.414 ms/op
     p(99.9999) =     49.414 ms/op
    p(100.0000) =     49.414 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.068 ms/op
Iteration   1: 1.959 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.561 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  22.413 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16415
  mean =      1.959 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15380 
    [ 2.500,  5.000) = 906 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.561 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 3.213 ±(99.9%) 0.085 ms/op
Iteration   1: 1.979 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   1.858 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.613 ms/op
                 getUser·p0.99:   4.403 ms/op
                 getUser·p0.999:  18.766 ms/op
                 getUser·p0.9999: 19.051 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16156
  mean =      1.979 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 14547 
    [ 2.500,  3.750) = 951 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      4.403 ms/op
     p(99.9000) =     18.766 ms/op
     p(99.9900) =     19.051 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.138 ms/op
Iteration   1: 3.415 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.573 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  7.443 ms/op
                 listUser·p0.9999: 8.847 ms/op
                 listUser·p1.00:   8.847 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9394
  mean =      3.415 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 13 
    [2.000, 2.500) = 57 
    [2.500, 3.000) = 2386 
    [3.000, 3.500) = 3594 
    [3.500, 4.000) = 1613 
    [4.000, 4.500) = 1381 
    [4.500, 5.000) = 169 
    [5.000, 5.500) = 106 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 14 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      7.443 ms/op
     p(99.9900) =      8.847 ms/op
     p(99.9990) =      8.847 ms/op
     p(99.9999) =      8.847 ms/op
    p(100.0000) =      8.847 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.188          ops/ms
ClientSimple.existUser                       thrpt         11.919          ops/ms
ClientSimple.getUser                         thrpt         12.779          ops/ms
ClientSimple.listUser                        thrpt          8.898          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.798           ms/op
ClientSimple.getUser                          avgt          1.975           ms/op
ClientSimple.listUser                         avgt          3.549           ms/op
ClientSimple.createUser                     sample  13621   2.347 ± 0.070   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.543           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.083           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.578           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.040           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         48.963           ms/op
ClientSimple.createUser:createUser·p1.00    sample         49.414           ms/op
ClientSimple.existUser                      sample  16415   1.959 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.561           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.116           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.413           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.839           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.839           ms/op
ClientSimple.getUser                        sample  16156   1.979 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.716           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.858           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.403           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.766           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.051           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.071           ms/op
ClientSimple.listUser                       sample   9394   3.415 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.573           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.341           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.443           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.847           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.847           ms/op

Benchmark result is saved to 1720030364130.json
