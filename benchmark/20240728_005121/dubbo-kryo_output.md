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
# Warmup Iteration   1: 1.974 ops/ms
Iteration   1: 7.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.100 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.852 ops/ms
Iteration   1: 12.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.787 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.154 ops/ms
Iteration   1: 14.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.020 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.548 ops/ms
Iteration   1: 8.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.023 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.064 ms/op
Iteration   1: 2.675 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.675 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ±(99.9%) 0.054 ms/op
Iteration   1: 2.144 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.144 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ±(99.9%) 0.062 ms/op
Iteration   1: 1.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.964 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ±(99.9%) 0.117 ms/op
Iteration   1: 3.613 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.613 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.408 ±(99.9%) 0.085 ms/op
Iteration   1: 2.356 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   5.622 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 16.214 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13569
  mean =      2.356 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 9264 
    [ 2.500,  3.750) = 3927 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      5.622 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     16.214 ms/op
     p(99.9990) =     16.220 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 2.854 ±(99.9%) 0.062 ms/op
Iteration   1: 1.709 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.087 ms/op
                 existUser·p0.95:   2.306 ms/op
                 existUser·p0.99:   2.752 ms/op
                 existUser·p0.999:  15.804 ms/op
                 existUser·p0.9999: 16.304 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18701
  mean =      1.709 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1168 
    [ 1.250,  2.500) = 17181 
    [ 2.500,  3.750) = 271 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.087 ms/op
     p(95.0000) =      2.306 ms/op
     p(99.0000) =      2.752 ms/op
     p(99.9000) =     15.804 ms/op
     p(99.9900) =     16.304 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.104 ms/op
Iteration   1: 2.169 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   4.392 ms/op
                 getUser·p0.999:  14.290 ms/op
                 getUser·p0.9999: 14.909 ms/op
                 getUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14791
  mean =      2.169 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 12358 
    [ 2.500,  3.750) = 2098 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.392 ms/op
     p(99.9000) =     14.290 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.113 ms/op
Iteration   1: 3.244 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.060 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  22.942 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9856
  mean =      3.244 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1571 
    [ 2.500,  5.000) = 8048 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.060 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     22.942 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.100          ops/ms
ClientSimple.existUser                       thrpt         12.787          ops/ms
ClientSimple.getUser                         thrpt         14.020          ops/ms
ClientSimple.listUser                        thrpt          8.023          ops/ms
ClientSimple.createUser                       avgt          2.675           ms/op
ClientSimple.existUser                        avgt          2.144           ms/op
ClientSimple.getUser                          avgt          1.964           ms/op
ClientSimple.listUser                         avgt          3.613           ms/op
ClientSimple.createUser                     sample  13569   2.356 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.666           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.248           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.622           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.190           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.214           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.220           ms/op
ClientSimple.existUser                      sample  18701   1.709 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.542           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.087           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.752           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.804           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.304           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.646           ms/op
ClientSimple.getUser                        sample  14791   2.169 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.392           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.290           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.909           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.909           ms/op
ClientSimple.listUser                       sample   9856   3.244 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.023           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.060           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.726           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.942           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.724           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.724           ms/op

Benchmark result is saved to 1722127605170.json
