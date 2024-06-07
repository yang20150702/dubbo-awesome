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
# Warmup Iteration   1: 1.373 ops/ms
Iteration   1: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.761 ops/ms


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
# Warmup Iteration   1: 4.729 ops/ms
Iteration   1: 13.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.007 ops/ms


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
# Warmup Iteration   1: 5.245 ops/ms
Iteration   1: 11.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.551 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.523 ops/ms


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.079 ms/op
Iteration   1: 2.075 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.075 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.051 ms/op
Iteration   1: 1.889 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.889 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.052 ms/op
Iteration   1: 1.856 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.856 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.102 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.123 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.073 ms/op
Iteration   1: 2.047 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.642 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  23.605 ms/op
                 createUser·p0.9999: 24.203 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15624
  mean =      2.047 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14394 
    [ 2.500,  5.000) = 1068 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     23.605 ms/op
     p(99.9900) =     24.203 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ±(99.9%) 0.087 ms/op
Iteration   1: 1.790 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.410 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 11.734 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17849
  mean =      1.790 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 808 
    [ 1.250,  2.500) = 16295 
    [ 2.500,  3.750) = 560 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.410 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     11.734 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.082 ms/op
Iteration   1: 2.020 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   4.590 ms/op
                 getUser·p0.999:  14.134 ms/op
                 getUser·p0.9999: 14.491 ms/op
                 getUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15864
  mean =      2.020 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 14337 
    [ 2.500,  3.750) = 1026 
    [ 3.750,  5.000) = 193 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      4.590 ms/op
     p(99.9000) =     14.134 ms/op
     p(99.9900) =     14.491 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.135 ms/op
Iteration   1: 3.258 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.383 ms/op
                 listUser·p0.999:  9.653 ms/op
                 listUser·p0.9999: 9.765 ms/op
                 listUser·p1.00:   9.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9840
  mean =      3.258 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 11 
    [ 1.500,  2.000) = 50 
    [ 2.000,  2.500) = 1553 
    [ 2.500,  3.000) = 2503 
    [ 3.000,  3.500) = 2256 
    [ 3.500,  4.000) = 2414 
    [ 4.000,  4.500) = 591 
    [ 4.500,  5.000) = 170 
    [ 5.000,  5.500) = 112 
    [ 5.500,  6.000) = 33 
    [ 6.000,  6.500) = 62 
    [ 6.500,  7.000) = 45 
    [ 7.000,  7.500) = 5 
    [ 7.500,  8.000) = 7 
    [ 8.000,  8.500) = 11 
    [ 8.500,  9.000) = 6 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.383 ms/op
     p(99.9000) =      9.653 ms/op
     p(99.9900) =      9.765 ms/op
     p(99.9990) =      9.765 ms/op
     p(99.9999) =      9.765 ms/op
    p(100.0000) =      9.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.761          ops/ms
ClientSimple.existUser                       thrpt         13.007          ops/ms
ClientSimple.getUser                         thrpt         11.551          ops/ms
ClientSimple.listUser                        thrpt          8.523          ops/ms
ClientSimple.createUser                       avgt          2.075           ms/op
ClientSimple.existUser                        avgt          1.889           ms/op
ClientSimple.getUser                          avgt          1.856           ms/op
ClientSimple.listUser                         avgt          3.123           ms/op
ClientSimple.createUser                     sample  15624   2.047 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.529           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.890           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.605           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.203           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.314           ms/op
ClientSimple.existUser                      sample  17849   1.790 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.397           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.714           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.410           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.781           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.583           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.734           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.747           ms/op
ClientSimple.getUser                        sample  15864   2.020 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.547           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.590           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.134           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.491           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.549           ms/op
ClientSimple.listUser                       sample   9840   3.258 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.313           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.248           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.383           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.653           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.765           ms/op

Benchmark result is saved to 1717740800867.json
