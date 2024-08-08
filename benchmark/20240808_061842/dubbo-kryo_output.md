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
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 7.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.323 ops/ms


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
# Warmup Iteration   1: 6.062 ops/ms
Iteration   1: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.849 ops/ms


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
# Warmup Iteration   1: 5.375 ops/ms
Iteration   1: 12.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.244 ops/ms


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
# Warmup Iteration   1: 3.832 ops/ms
Iteration   1: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.256 ops/ms


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.082 ms/op
Iteration   1: 2.125 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.125 ms/op


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
# Warmup Iteration   1: 2.823 ±(99.9%) 0.044 ms/op
Iteration   1: 2.068 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.058 ms/op
Iteration   1: 1.810 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.810 ms/op


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.095 ms/op
Iteration   1: 3.295 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.295 ms/op


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
# Warmup Iteration   1: 3.433 ±(99.9%) 0.100 ms/op
Iteration   1: 2.115 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   8.824 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15113
  mean =      2.115 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13432 
    [ 2.500,  5.000) = 1369 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      8.824 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.072 ms/op
Iteration   1: 1.821 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.311 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 11.566 ms/op
                 existUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17555
  mean =      1.821 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1027 
    [ 1.250,  2.500) = 15979 
    [ 2.500,  3.750) = 393 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     11.566 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.078 ms/op
Iteration   1: 2.036 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.423 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.871 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  26.519 ms/op
                 getUser·p0.9999: 27.506 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15712
  mean =      2.036 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12990 
    [ 2.500,  5.000) = 2651 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =     26.519 ms/op
     p(99.9900) =     27.506 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.129 ms/op
Iteration   1: 3.156 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  11.581 ms/op
                 listUser·p0.9999: 13.671 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10133
  mean =      3.156 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 187 
    [ 2.500,  3.750) = 8429 
    [ 3.750,  5.000) = 1318 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     11.581 ms/op
     p(99.9900) =     13.671 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.323          ops/ms
ClientSimple.existUser                       thrpt         12.849          ops/ms
ClientSimple.getUser                         thrpt         12.244          ops/ms
ClientSimple.listUser                        thrpt          8.256          ops/ms
ClientSimple.createUser                       avgt          2.125           ms/op
ClientSimple.existUser                        avgt          2.068           ms/op
ClientSimple.getUser                          avgt          1.810           ms/op
ClientSimple.listUser                         avgt          3.295           ms/op
ClientSimple.createUser                     sample  15113   2.115 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.824           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.708           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.495           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.495           ms/op
ClientSimple.existUser                      sample  17555   1.821 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.311           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.518           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.108           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.566           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.665           ms/op
ClientSimple.getUser                        sample  15712   2.036 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.423           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.846           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.519           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.506           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.525           ms/op
ClientSimple.listUser                       sample  10133   3.156 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.827           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.480           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.581           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.671           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.697           ms/op

Benchmark result is saved to 1723097679085.json
