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
# Warmup Iteration   1: 1.700 ops/ms
Iteration   1: 6.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.673 ops/ms


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
# Warmup Iteration   1: 5.462 ops/ms
Iteration   1: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.759 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.292 ops/ms
Iteration   1: 12.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.113 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ops/ms
Iteration   1: 7.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.527 ops/ms


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.087 ms/op
Iteration   1: 2.120 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.120 ms/op


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
# Warmup Iteration   1: 3.367 ±(99.9%) 0.053 ms/op
Iteration   1: 2.079 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.065 ms/op
Iteration   1: 2.334 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.334 ms/op


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.096 ms/op
Iteration   1: 3.715 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.715 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.094 ms/op
Iteration   1: 2.533 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   2.265 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.767 ms/op
                 createUser·p0.99:   12.993 ms/op
                 createUser·p0.999:  30.240 ms/op
                 createUser·p0.9999: 38.611 ms/op
                 createUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12632
  mean =      2.533 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8515 
    [ 2.500,  5.000) = 3760 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.767 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     30.240 ms/op
     p(99.9900) =     38.611 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.103 ms/op
Iteration   1: 1.997 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.048 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 11.871 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16064
  mean =      1.997 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 14256 
    [ 2.500,  3.750) = 1343 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.048 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     11.871 ms/op
     p(99.9990) =     11.960 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


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
# Warmup Iteration   1: 3.553 ±(99.9%) 0.124 ms/op
Iteration   1: 1.916 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 11.196 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16680
  mean =      1.916 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 14825 
    [ 2.500,  3.750) = 1275 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     11.196 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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
# Warmup Iteration   1: 4.739 ±(99.9%) 0.160 ms/op
Iteration   1: 3.366 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   3.125 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.050 ms/op
                 listUser·p0.999:  17.026 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9473
  mean =      3.366 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 677 
    [ 2.500,  3.750) = 6337 
    [ 3.750,  5.000) = 2153 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.050 ms/op
     p(99.9000) =     17.026 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.673          ops/ms
ClientSimple.existUser                       thrpt         12.759          ops/ms
ClientSimple.getUser                         thrpt         12.113          ops/ms
ClientSimple.listUser                        thrpt          7.527          ops/ms
ClientSimple.createUser                       avgt          2.120           ms/op
ClientSimple.existUser                        avgt          2.079           ms/op
ClientSimple.getUser                          avgt          2.334           ms/op
ClientSimple.listUser                         avgt          3.715           ms/op
ClientSimple.createUser                     sample  12632   2.533 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.774           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.265           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.767           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.240           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.611           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.387           ms/op
ClientSimple.existUser                      sample  16064   1.997 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.048           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.747           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.871           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.960           ms/op
ClientSimple.getUser                        sample  16680   1.916 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.535           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.196           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.239           ms/op
ClientSimple.listUser                       sample   9473   3.366 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.990           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.125           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.050           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.026           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.465           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.465           ms/op

Benchmark result is saved to 1714696826157.json
