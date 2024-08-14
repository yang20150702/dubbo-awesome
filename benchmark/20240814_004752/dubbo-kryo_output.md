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
# Warmup Iteration   1: 1.890 ops/ms
Iteration   1: 7.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.544 ops/ms


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
# Warmup Iteration   1: 5.946 ops/ms
Iteration   1: 11.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.373 ops/ms


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
# Warmup Iteration   1: 6.538 ops/ms
Iteration   1: 13.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.805 ops/ms


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
# Warmup Iteration   1: 4.929 ops/ms
Iteration   1: 8.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.332 ops/ms


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.065 ms/op
Iteration   1: 2.207 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.100 ms/op
Iteration   1: 1.865 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.865 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.058 ms/op
Iteration   1: 2.149 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.149 ms/op


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
# Warmup Iteration   1: 5.716 ±(99.9%) 0.102 ms/op
Iteration   1: 3.384 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.384 ms/op


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
# Warmup Iteration   1: 3.627 ±(99.9%) 0.101 ms/op
Iteration   1: 2.194 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  27.998 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14562
  mean =      2.194 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12758 
    [ 2.500,  5.000) = 1529 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     27.998 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.139 ms/op
Iteration   1: 1.865 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   4.388 ms/op
                 existUser·p0.999:  10.804 ms/op
                 existUser·p0.9999: 11.277 ms/op
                 existUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17138
  mean =      1.865 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 457 
    [ 1.250,  2.500) = 15885 
    [ 2.500,  3.750) = 611 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      4.388 ms/op
     p(99.9000) =     10.804 ms/op
     p(99.9900) =     11.277 ms/op
     p(99.9990) =     11.289 ms/op
     p(99.9999) =     11.289 ms/op
    p(100.0000) =     11.289 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.088 ms/op
Iteration   1: 1.994 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.652 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 23.151 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16031
  mean =      1.994 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14570 
    [ 2.500,  5.000) = 1349 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.652 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     23.151 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.162 ms/op
Iteration   1: 3.536 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.817 ms/op
                 listUser·p0.999:  21.789 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9039
  mean =      3.536 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1393 
    [ 2.500,  5.000) = 7301 
    [ 5.000,  7.500) = 281 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.817 ms/op
     p(99.9000) =     21.789 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.544          ops/ms
ClientSimple.existUser                       thrpt         11.373          ops/ms
ClientSimple.getUser                         thrpt         13.805          ops/ms
ClientSimple.listUser                        thrpt          8.332          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          1.865           ms/op
ClientSimple.getUser                          avgt          2.149           ms/op
ClientSimple.listUser                         avgt          3.384           ms/op
ClientSimple.createUser                     sample  14562   2.194 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.653           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.998           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.967           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.967           ms/op
ClientSimple.existUser                      sample  17138   1.865 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.388           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.804           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.277           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.289           ms/op
ClientSimple.getUser                        sample  16031   1.994 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.775           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.652           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.613           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.906           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.151           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.724           ms/op
ClientSimple.listUser                       sample   9039   3.536 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.701           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.817           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.789           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.118           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.118           ms/op

Benchmark result is saved to 1723596213441.json
