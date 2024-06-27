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
# Warmup Iteration   1: 2.108 ops/ms
Iteration   1: 7.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.483 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ops/ms
Iteration   1: 12.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.320 ops/ms


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
# Warmup Iteration   1: 6.217 ops/ms
Iteration   1: 14.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.095 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.573 ops/ms
Iteration   1: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.529 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.069 ms/op
Iteration   1: 2.082 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.082 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.054 ms/op
Iteration   1: 2.069 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.069 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.064 ms/op
Iteration   1: 1.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.994 ms/op


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.075 ms/op
Iteration   1: 3.382 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.382 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.077 ms/op
Iteration   1: 2.218 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   3.194 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 21.481 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14415
  mean =      2.218 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11622 
    [ 2.500,  5.000) = 2745 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.194 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     21.481 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 2.932 ±(99.9%) 0.071 ms/op
Iteration   1: 1.722 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   1.862 ms/op
                 existUser·p0.95:   2.122 ms/op
                 existUser·p0.99:   3.451 ms/op
                 existUser·p0.999:  24.275 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18594
  mean =      1.722 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18212 
    [ 2.500,  5.000) = 263 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      1.862 ms/op
     p(95.0000) =      2.122 ms/op
     p(99.0000) =      3.451 ms/op
     p(99.9000) =     24.275 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.087 ms/op
Iteration   1: 2.180 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  15.319 ms/op
                 getUser·p0.9999: 16.094 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14660
  mean =      2.180 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 11641 
    [ 2.500,  3.750) = 2719 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     16.094 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.120 ms/op
Iteration   1: 3.265 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.645 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   4.981 ms/op
                 listUser·p0.999:  7.838 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9795
  mean =      3.265 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 684 
    [ 2.500,  3.750) = 6692 
    [ 3.750,  5.000) = 2310 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      7.838 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.483          ops/ms
ClientSimple.existUser                       thrpt         12.320          ops/ms
ClientSimple.getUser                         thrpt         14.095          ops/ms
ClientSimple.listUser                        thrpt          8.529          ops/ms
ClientSimple.createUser                       avgt          2.082           ms/op
ClientSimple.existUser                        avgt          2.069           ms/op
ClientSimple.getUser                          avgt          1.994           ms/op
ClientSimple.listUser                         avgt          3.382           ms/op
ClientSimple.createUser                     sample  14415   2.218 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.763           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.194           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.300           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.481           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.496           ms/op
ClientSimple.existUser                      sample  18594   1.722 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.451           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.275           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.131           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.131           ms/op
ClientSimple.getUser                        sample  14660   2.180 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.637           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.178           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.319           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.094           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.155           ms/op
ClientSimple.listUser                       sample   9795   3.265 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.645           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.838           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.305           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.305           ms/op

Benchmark result is saved to 1719448873905.json
