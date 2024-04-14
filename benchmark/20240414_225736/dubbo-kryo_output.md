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
# Warmup Iteration   1: 1.032 ops/ms
Iteration   1: 6.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.108 ops/ms


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
# Warmup Iteration   1: 5.874 ops/ms
Iteration   1: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.734 ops/ms


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
# Warmup Iteration   1: 5.665 ops/ms
Iteration   1: 11.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.263 ops/ms


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
# Warmup Iteration   1: 3.718 ops/ms
Iteration   1: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.806 ops/ms


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.079 ms/op
Iteration   1: 2.066 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.066 ms/op


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
# Warmup Iteration   1: 2.980 ±(99.9%) 0.049 ms/op
Iteration   1: 1.794 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.794 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.061 ms/op
Iteration   1: 2.192 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.192 ms/op


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.098 ms/op
Iteration   1: 3.633 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.633 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.094 ms/op
Iteration   1: 2.105 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.573 ms/op
                 createUser·p0.95:   2.839 ms/op
                 createUser·p0.99:   5.360 ms/op
                 createUser·p0.999:  15.024 ms/op
                 createUser·p0.9999: 15.770 ms/op
                 createUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15187
  mean =      2.105 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 13195 
    [ 2.500,  3.750) = 1561 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.573 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      5.360 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     15.770 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.078 ms/op
Iteration   1: 1.807 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   3.026 ms/op
                 existUser·p0.999:  18.883 ms/op
                 existUser·p0.9999: 19.690 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17734
  mean =      1.807 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 16843 
    [ 2.500,  3.750) = 512 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      3.026 ms/op
     p(99.9000) =     18.883 ms/op
     p(99.9900) =     19.690 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.089 ms/op
Iteration   1: 2.107 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   4.031 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 11.985 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15180
  mean =      2.107 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 13215 
    [ 2.500,  3.750) = 1696 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      4.031 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     11.985 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.146 ms/op
Iteration   1: 3.258 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  7.945 ms/op
                 listUser·p0.9999: 9.110 ms/op
                 listUser·p1.00:   9.110 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9825
  mean =      3.258 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 4 
    [ 1.500,  2.000) = 50 
    [ 2.000,  2.500) = 845 
    [ 2.500,  3.000) = 4080 
    [ 3.000,  3.500) = 1679 
    [ 3.500,  4.000) = 1565 
    [ 4.000,  4.500) = 1146 
    [ 4.500,  5.000) = 184 
    [ 5.000,  5.500) = 84 
    [ 5.500,  6.000) = 33 
    [ 6.000,  6.500) = 52 
    [ 6.500,  7.000) = 32 
    [ 7.000,  7.500) = 21 
    [ 7.500,  8.000) = 42 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =      7.945 ms/op
     p(99.9900) =      9.110 ms/op
     p(99.9990) =      9.110 ms/op
     p(99.9999) =      9.110 ms/op
    p(100.0000) =      9.110 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.108          ops/ms
ClientSimple.existUser                       thrpt         10.734          ops/ms
ClientSimple.getUser                         thrpt         11.263          ops/ms
ClientSimple.listUser                        thrpt          7.806          ops/ms
ClientSimple.createUser                       avgt          2.066           ms/op
ClientSimple.existUser                        avgt          1.794           ms/op
ClientSimple.getUser                          avgt          2.192           ms/op
ClientSimple.listUser                         avgt          3.633           ms/op
ClientSimple.createUser                     sample  15187   2.105 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.506           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.573           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.360           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.024           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.770           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.991           ms/op
ClientSimple.existUser                      sample  17734   1.807 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.720           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.026           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.883           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.690           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.792           ms/op
ClientSimple.getUser                        sample  15180   2.107 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.865           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.031           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.796           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.985           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.993           ms/op
ClientSimple.listUser                       sample   9825   3.258 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.350           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.986           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.945           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.110           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.110           ms/op

Benchmark result is saved to 1713135174015.json
