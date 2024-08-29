# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.764 ops/ms
Iteration   1: 6.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.362 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ops/ms
Iteration   1: 11.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.563 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.840 ops/ms
Iteration   1: 11.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.482 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.351 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ±(99.9%) 0.081 ms/op
Iteration   1: 2.701 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.701 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ±(99.9%) 0.054 ms/op
Iteration   1: 1.983 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ±(99.9%) 0.061 ms/op
Iteration   1: 1.979 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.606 ±(99.9%) 0.105 ms/op
Iteration   1: 3.679 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.098 ms/op
Iteration   1: 2.369 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.748 ms/op
                 createUser·p0.95:   3.402 ms/op
                 createUser·p0.99:   11.374 ms/op
                 createUser·p0.999:  35.324 ms/op
                 createUser·p0.9999: 35.563 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13489
  mean =      2.369 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11178 
    [ 2.500,  5.000) = 1949 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.402 ms/op
     p(99.0000) =     11.374 ms/op
     p(99.9000) =     35.324 ms/op
     p(99.9900) =     35.563 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ±(99.9%) 0.101 ms/op
Iteration   1: 1.929 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   4.089 ms/op
                 existUser·p0.999:  10.165 ms/op
                 existUser·p0.9999: 10.256 ms/op
                 existUser·p1.00:   10.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16567
  mean =      1.929 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 105 
    [ 1.000,  2.000) = 10714 
    [ 2.000,  3.000) = 5229 
    [ 3.000,  4.000) = 328 
    [ 4.000,  5.000) = 92 
    [ 5.000,  6.000) = 30 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 24 
    [ 8.000,  9.000) = 12 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.089 ms/op
     p(99.9000) =     10.165 ms/op
     p(99.9900) =     10.256 ms/op
     p(99.9990) =     10.256 ms/op
     p(99.9999) =     10.256 ms/op
    p(100.0000) =     10.256 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.087 ms/op
Iteration   1: 2.248 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.974 ms/op
                 getUser·p0.999:  27.404 ms/op
                 getUser·p0.9999: 27.773 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14340
  mean =      2.248 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9595 
    [ 2.500,  5.000) = 4606 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.974 ms/op
     p(99.9000) =     27.404 ms/op
     p(99.9900) =     27.773 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.963 ±(99.9%) 0.160 ms/op
Iteration   1: 3.715 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.002 ms/op
                 listUser·p0.999:  23.793 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8627
  mean =      3.715 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 560 
    [ 2.500,  5.000) = 7828 
    [ 5.000,  7.500) = 175 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.002 ms/op
     p(99.9000) =     23.793 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.362          ops/ms
ClientSimple.existUser                       thrpt         11.563          ops/ms
ClientSimple.getUser                         thrpt         11.482          ops/ms
ClientSimple.listUser                        thrpt          8.351          ops/ms
ClientSimple.createUser                       avgt          2.701           ms/op
ClientSimple.existUser                        avgt          1.983           ms/op
ClientSimple.getUser                          avgt          1.979           ms/op
ClientSimple.listUser                         avgt          3.679           ms/op
ClientSimple.createUser                     sample  13489   2.369 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.526           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.402           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.374           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.324           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.563           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.586           ms/op
ClientSimple.existUser                      sample  16567   1.929 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.626           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.089           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.165           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.256           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.256           ms/op
ClientSimple.getUser                        sample  14340   2.248 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.538           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.166           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.974           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.404           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.773           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.787           ms/op
ClientSimple.listUser                       sample   8627   3.715 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.979           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.715           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.002           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.002           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.002           ms/op

Benchmark result is saved to 1724892284612.json
