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
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 7.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.551 ops/ms


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
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 12.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.189 ops/ms


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
# Warmup Iteration   1: 5.271 ops/ms
Iteration   1: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.894 ops/ms


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
# Warmup Iteration   1: 4.175 ops/ms
Iteration   1: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.736 ops/ms


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.084 ms/op
Iteration   1: 2.223 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.223 ms/op


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
# Warmup Iteration   1: 3.437 ±(99.9%) 0.073 ms/op
Iteration   1: 2.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.013 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.061 ms/op
Iteration   1: 2.042 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.092 ms/op
Iteration   1: 3.764 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.764 ms/op


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.225 ms/op
Iteration   1: 2.236 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   10.257 ms/op
                 createUser·p0.999:  18.826 ms/op
                 createUser·p0.9999: 19.436 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14295
  mean =      2.236 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 375 
    [ 1.250,  2.500) = 12388 
    [ 2.500,  3.750) = 934 
    [ 3.750,  5.000) = 244 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      3.318 ms/op
     p(99.0000) =     10.257 ms/op
     p(99.9000) =     18.826 ms/op
     p(99.9900) =     19.436 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.077 ms/op
Iteration   1: 1.840 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.489 ms/op
                 existUser·p0.99:   3.229 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 15.694 ms/op
                 existUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17667
  mean =      1.840 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 454 
    [ 1.250,  2.500) = 16371 
    [ 2.500,  3.750) = 724 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.489 ms/op
     p(99.0000) =      3.229 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     15.694 ms/op
     p(99.9990) =     15.794 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.094 ms/op
Iteration   1: 2.029 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 13.119 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16509
  mean =      2.029 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 14733 
    [ 2.500,  3.750) = 1379 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     13.119 ms/op
     p(99.9990) =     13.140 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.140 ms/op
Iteration   1: 3.396 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.277 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  6.973 ms/op
                 listUser·p0.9999: 7.258 ms/op
                 listUser·p1.00:   7.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9415
  mean =      3.396 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 25 
    [2.000, 2.500) = 468 
    [2.500, 3.000) = 3186 
    [3.000, 3.500) = 1973 
    [3.500, 4.000) = 1884 
    [4.000, 4.500) = 1198 
    [4.500, 5.000) = 383 
    [5.000, 5.500) = 126 
    [5.500, 6.000) = 68 
    [6.000, 6.500) = 83 
    [6.500, 7.000) = 12 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =      6.973 ms/op
     p(99.9900) =      7.258 ms/op
     p(99.9990) =      7.258 ms/op
     p(99.9999) =      7.258 ms/op
    p(100.0000) =      7.258 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.551          ops/ms
ClientSimple.existUser                       thrpt         12.189          ops/ms
ClientSimple.getUser                         thrpt         12.894          ops/ms
ClientSimple.listUser                        thrpt          8.736          ops/ms
ClientSimple.createUser                       avgt          2.223           ms/op
ClientSimple.existUser                        avgt          2.013           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.764           ms/op
ClientSimple.createUser                     sample  14295   2.236 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.673           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.318           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.257           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.826           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.436           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.464           ms/op
ClientSimple.existUser                      sample  17667   1.840 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.489           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.229           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.483           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.694           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.794           ms/op
ClientSimple.getUser                        sample  16509   2.029 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.663           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.432           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.119           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.140           ms/op
ClientSimple.listUser                       sample   9415   3.396 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.277           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.973           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.258           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.258           ms/op

Benchmark result is saved to 1717634402458.json
