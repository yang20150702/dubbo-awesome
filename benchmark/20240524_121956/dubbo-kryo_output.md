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
# Warmup Iteration   1: 1.576 ops/ms
Iteration   1: 7.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.078 ops/ms


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
# Warmup Iteration   1: 5.129 ops/ms
Iteration   1: 14.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.021 ops/ms


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
# Warmup Iteration   1: 5.000 ops/ms
Iteration   1: 11.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.345 ops/ms


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
# Warmup Iteration   1: 4.853 ops/ms
Iteration   1: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.584 ops/ms


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.083 ms/op
Iteration   1: 2.036 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.036 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.053 ms/op
Iteration   1: 1.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.969 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.052 ms/op
Iteration   1: 2.100 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.100 ms/op


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.087 ms/op
Iteration   1: 3.521 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.521 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.084 ms/op
Iteration   1: 2.151 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   4.175 ms/op
                 createUser·p0.999:  44.958 ms/op
                 createUser·p0.9999: 46.860 ms/op
                 createUser·p1.00:   46.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14872
  mean =      2.151 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14763 
    [ 5.000, 10.000) = 46 
    [10.000, 15.000) = 31 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.175 ms/op
     p(99.9000) =     44.958 ms/op
     p(99.9900) =     46.860 ms/op
     p(99.9990) =     46.924 ms/op
     p(99.9999) =     46.924 ms/op
    p(100.0000) =     46.924 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.083 ms/op
Iteration   1: 1.787 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.089 ms/op
                 existUser·p0.95:   2.265 ms/op
                 existUser·p0.99:   2.895 ms/op
                 existUser·p0.999:  22.908 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17911
  mean =      1.787 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17473 
    [ 2.500,  5.000) = 358 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.265 ms/op
     p(99.0000) =      2.895 ms/op
     p(99.9000) =     22.908 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.198 ms/op
Iteration   1: 1.952 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   1.823 ms/op
                 getUser·p0.90:   2.345 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   3.122 ms/op
                 getUser·p0.999:  18.817 ms/op
                 getUser·p0.9999: 19.458 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16373
  mean =      1.952 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 15423 
    [ 2.500,  3.750) = 802 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.345 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.122 ms/op
     p(99.9000) =     18.817 ms/op
     p(99.9900) =     19.458 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.125 ms/op
Iteration   1: 3.438 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.678 ms/op
                 listUser·p0.50:   3.379 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   5.746 ms/op
                 listUser·p0.999:  22.158 ms/op
                 listUser·p0.9999: 27.099 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9559
  mean =      3.438 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1590 
    [ 2.500,  5.000) = 7685 
    [ 5.000,  7.500) = 248 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.746 ms/op
     p(99.9000) =     22.158 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.078          ops/ms
ClientSimple.existUser                       thrpt         14.021          ops/ms
ClientSimple.getUser                         thrpt         11.345          ops/ms
ClientSimple.listUser                        thrpt          8.584          ops/ms
ClientSimple.createUser                       avgt          2.036           ms/op
ClientSimple.existUser                        avgt          1.969           ms/op
ClientSimple.getUser                          avgt          2.100           ms/op
ClientSimple.listUser                         avgt          3.521           ms/op
ClientSimple.createUser                     sample  14872   2.151 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.732           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.175           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.958           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         46.860           ms/op
ClientSimple.createUser:createUser·p1.00    sample         46.924           ms/op
ClientSimple.existUser                      sample  17911   1.787 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.764           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.667           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.089           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.895           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.908           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.003           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.003           ms/op
ClientSimple.getUser                        sample  16373   1.952 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.821           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.823           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.345           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.122           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.817           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.458           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.562           ms/op
ClientSimple.listUser                       sample   9559   3.438 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.678           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.379           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.746           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.158           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.099           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.099           ms/op

Benchmark result is saved to 1716552943080.json
