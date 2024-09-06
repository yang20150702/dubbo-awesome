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
# Warmup Iteration   1: 1.339 ops/ms
Iteration   1: 7.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.262 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.947 ops/ms
Iteration   1: 11.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.627 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.949 ops/ms
Iteration   1: 13.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.967 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ops/ms
Iteration   1: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.047 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ±(99.9%) 0.085 ms/op
Iteration   1: 2.414 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.414 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ±(99.9%) 0.052 ms/op
Iteration   1: 1.988 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.988 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.076 ms/op
Iteration   1: 2.191 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.191 ms/op


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
# Warmup Iteration   1: 5.609 ±(99.9%) 0.124 ms/op
Iteration   1: 3.975 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.975 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.126 ms/op
Iteration   1: 2.252 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   2.073 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  16.676 ms/op
                 createUser·p0.9999: 17.457 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14200
  mean =      2.252 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 11391 
    [ 2.500,  3.750) = 2128 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.073 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.676 ms/op
     p(99.9900) =     17.457 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.079 ms/op
Iteration   1: 2.029 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   5.073 ms/op
                 existUser·p0.999:  23.953 ms/op
                 existUser·p0.9999: 25.180 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15774
  mean =      2.029 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14281 
    [ 2.500,  5.000) = 1332 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      5.073 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     25.180 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.089 ms/op
Iteration   1: 2.179 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.986 ms/op
                 getUser·p0.99:   6.020 ms/op
                 getUser·p0.999:  14.041 ms/op
                 getUser·p0.9999: 14.334 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14651
  mean =      2.179 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 12549 
    [ 2.500,  3.750) = 1725 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      6.020 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     14.334 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.146 ms/op
Iteration   1: 3.318 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.722 ms/op
                 listUser·p0.99:   8.228 ms/op
                 listUser·p0.999:  21.705 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9630
  mean =      3.318 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1430 
    [ 2.500,  5.000) = 7878 
    [ 5.000,  7.500) = 220 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.722 ms/op
     p(99.0000) =      8.228 ms/op
     p(99.9000) =     21.705 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.262          ops/ms
ClientSimple.existUser                       thrpt         11.627          ops/ms
ClientSimple.getUser                         thrpt         13.967          ops/ms
ClientSimple.listUser                        thrpt          8.047          ops/ms
ClientSimple.createUser                       avgt          2.414           ms/op
ClientSimple.existUser                        avgt          1.988           ms/op
ClientSimple.getUser                          avgt          2.191           ms/op
ClientSimple.listUser                         avgt          3.975           ms/op
ClientSimple.createUser                     sample  14200   2.252 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.391           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.073           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.037           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.676           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.457           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.498           ms/op
ClientSimple.existUser                      sample  15774   2.029 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.753           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.073           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.953           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.180           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.199           ms/op
ClientSimple.getUser                        sample  14651   2.179 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.044           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.986           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.020           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.041           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.334           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.418           ms/op
ClientSimple.listUser                       sample   9630   3.318 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.075           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.072           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.722           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.228           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.705           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.839           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.839           ms/op

Benchmark result is saved to 1725646381469.json
