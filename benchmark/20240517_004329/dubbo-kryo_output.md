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
# Warmup Iteration   1: 1.881 ops/ms
Iteration   1: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.792 ops/ms


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
# Warmup Iteration   1: 5.977 ops/ms
Iteration   1: 13.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.861 ops/ms


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
# Warmup Iteration   1: 6.003 ops/ms
Iteration   1: 12.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.030 ops/ms


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
# Warmup Iteration   1: 4.920 ops/ms
Iteration   1: 9.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.720 ops/ms


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.058 ms/op
Iteration   1: 2.091 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.091 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.049 ms/op
Iteration   1: 1.881 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 3.484 ±(99.9%) 0.063 ms/op
Iteration   1: 1.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.105 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.159 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.110 ms/op
Iteration   1: 2.157 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   12.599 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14820
  mean =      2.157 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13698 
    [ 2.500,  5.000) = 935 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 2.853 ±(99.9%) 0.060 ms/op
Iteration   1: 1.852 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 18.223 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17355
  mean =      1.852 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 16814 
    [ 2.500,  3.750) = 337 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     18.223 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.077 ms/op
Iteration   1: 2.175 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.369 ms/op
                 getUser·p0.50:   2.134 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.717 ms/op
                 getUser·p0.999:  11.818 ms/op
                 getUser·p0.9999: 13.048 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14680
  mean =      2.175 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 12026 
    [ 2.500,  3.750) = 2326 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.717 ms/op
     p(99.9000) =     11.818 ms/op
     p(99.9900) =     13.048 ms/op
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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.124 ms/op
Iteration   1: 3.253 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.097 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.257 ms/op
                 listUser·p0.999:  7.333 ms/op
                 listUser·p0.9999: 8.405 ms/op
                 listUser·p1.00:   8.405 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9817
  mean =      3.253 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 224 
    [2.000, 2.500) = 1798 
    [2.500, 3.000) = 2650 
    [3.000, 3.500) = 1093 
    [3.500, 4.000) = 1908 
    [4.000, 4.500) = 1557 
    [4.500, 5.000) = 355 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 35 
    [6.000, 6.500) = 64 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 33 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.257 ms/op
     p(99.9000) =      7.333 ms/op
     p(99.9900) =      8.405 ms/op
     p(99.9990) =      8.405 ms/op
     p(99.9999) =      8.405 ms/op
    p(100.0000) =      8.405 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.792          ops/ms
ClientSimple.existUser                       thrpt         13.861          ops/ms
ClientSimple.getUser                         thrpt         12.030          ops/ms
ClientSimple.listUser                        thrpt          9.720          ops/ms
ClientSimple.createUser                       avgt          2.091           ms/op
ClientSimple.existUser                        avgt          1.881           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.159           ms/op
ClientSimple.createUser                     sample  14820   2.157 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.734           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.599           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.955           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.086           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.086           ms/op
ClientSimple.existUser                      sample  17355   1.852 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.751           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.433           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.223           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.416           ms/op
ClientSimple.getUser                        sample  14680   2.175 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.369           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.717           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.818           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.048           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.140           ms/op
ClientSimple.listUser                       sample   9817   3.253 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.096           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.097           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.257           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.405           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.405           ms/op

Benchmark result is saved to 1715906366332.json
