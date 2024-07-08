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
# Warmup Iteration   1: 1.449 ops/ms
Iteration   1: 6.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.830 ops/ms


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
# Warmup Iteration   1: 5.267 ops/ms
Iteration   1: 12.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.220 ops/ms


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
# Warmup Iteration   1: 6.022 ops/ms
Iteration   1: 12.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.236 ops/ms


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
# Warmup Iteration   1: 5.857 ops/ms
Iteration   1: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.173 ops/ms


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.071 ms/op
Iteration   1: 2.280 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.081 ms/op
Iteration   1: 2.047 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.047 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.063 ms/op
Iteration   1: 2.099 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.099 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.088 ms/op
Iteration   1: 3.451 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.451 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.075 ms/op
Iteration   1: 2.213 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   1.935 ms/op
                 createUser·p0.90:   2.548 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14453
  mean =      2.213 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12678 
    [ 2.500,  5.000) = 1499 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 2.921 ±(99.9%) 0.065 ms/op
Iteration   1: 1.814 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  14.244 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17619
  mean =      1.814 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 16494 
    [ 2.500,  3.750) = 812 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =     14.244 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.083 ms/op
Iteration   1: 2.127 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.064 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  7.078 ms/op
                 getUser·p0.9999: 8.323 ms/op
                 getUser·p1.00:   8.348 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15040
  mean =      2.127 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 32 
    [1.000, 1.500) = 764 
    [1.500, 2.000) = 5717 
    [2.000, 2.500) = 6361 
    [2.500, 3.000) = 1653 
    [3.000, 3.500) = 232 
    [3.500, 4.000) = 57 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 65 
    [5.000, 5.500) = 66 
    [5.500, 6.000) = 8 
    [6.000, 6.500) = 37 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 15 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =      8.323 ms/op
     p(99.9990) =      8.348 ms/op
     p(99.9999) =      8.348 ms/op
    p(100.0000) =      8.348 ms/op


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.198 ms/op
Iteration   1: 3.168 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.201 ms/op
                 listUser·p0.999:  8.828 ms/op
                 listUser·p0.9999: 11.716 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10194
  mean =      3.168 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 210 
    [ 2.500,  3.750) = 8511 
    [ 3.750,  5.000) = 1252 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =      8.828 ms/op
     p(99.9900) =     11.716 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.830          ops/ms
ClientSimple.existUser                       thrpt         12.220          ops/ms
ClientSimple.getUser                         thrpt         12.236          ops/ms
ClientSimple.listUser                        thrpt          8.173          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          2.047           ms/op
ClientSimple.getUser                          avgt          2.099           ms/op
ClientSimple.listUser                         avgt          3.451           ms/op
ClientSimple.createUser                     sample  14453   2.213 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.112           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.935           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.548           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.354           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.707           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.297           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.428           ms/op
ClientSimple.existUser                      sample  17619   1.814 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.709           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.669           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.551           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.244           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.369           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.369           ms/op
ClientSimple.getUser                        sample  15040   2.127 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.783           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.064           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.964           ms/op
ClientSimple.getUser:getUser·p0.999         sample          7.078           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.323           ms/op
ClientSimple.getUser:getUser·p1.00          sample          8.348           ms/op
ClientSimple.listUser                       sample  10194   3.168 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.522           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.949           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.201           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.828           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.716           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.747           ms/op

Benchmark result is saved to 1720419254261.json
