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
# Warmup Iteration   1: 1.866 ops/ms
Iteration   1: 6.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.807 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ops/ms
Iteration   1: 13.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.329 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.429 ops/ms
Iteration   1: 14.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.055 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.271 ops/ms
Iteration   1: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.117 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.419 ±(99.9%) 0.085 ms/op
Iteration   1: 2.319 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.319 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.052 ms/op
Iteration   1: 1.735 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.735 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.051 ms/op
Iteration   1: 2.116 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.116 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.094 ms/op
Iteration   1: 3.698 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.698 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.089 ms/op
Iteration   1: 2.273 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.480 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.855 ms/op
                 createUser·p0.95:   3.077 ms/op
                 createUser·p0.99:   5.107 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 25.846 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14035
  mean =      2.273 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10413 
    [ 2.500,  5.000) = 3482 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.077 ms/op
     p(99.0000) =      5.107 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     25.846 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ±(99.9%) 0.081 ms/op
Iteration   1: 2.035 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.948 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 11.680 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15680
  mean =      2.035 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 262 
    [ 1.250,  2.500) = 13749 
    [ 2.500,  3.750) = 1619 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     11.680 ms/op
     p(99.9990) =     11.829 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.085 ms/op
Iteration   1: 1.913 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   1.677 ms/op
                 getUser·p0.90:   2.515 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   3.428 ms/op
                 getUser·p0.999:  23.560 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17011
  mean =      1.913 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15258 
    [ 2.500,  5.000) = 1645 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.428 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.134 ms/op
Iteration   1: 3.325 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.395 ms/op
                 listUser·p0.999:  15.228 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9547
  mean =      3.325 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1828 
    [ 2.500,  3.750) = 4877 
    [ 3.750,  5.000) = 2639 
    [ 5.000,  6.250) = 186 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.395 ms/op
     p(99.9000) =     15.228 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.807          ops/ms
ClientSimple.existUser                       thrpt         13.329          ops/ms
ClientSimple.getUser                         thrpt         14.055          ops/ms
ClientSimple.listUser                        thrpt          8.117          ops/ms
ClientSimple.createUser                       avgt          2.319           ms/op
ClientSimple.existUser                        avgt          1.735           ms/op
ClientSimple.getUser                          avgt          2.116           ms/op
ClientSimple.listUser                         avgt          3.698           ms/op
ClientSimple.createUser                     sample  14035   2.273 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.480           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.077           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.107           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.381           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.846           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.018           ms/op
ClientSimple.existUser                      sample  15680   2.035 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.581           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.948           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.334           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.453           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.680           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.829           ms/op
ClientSimple.getUser                        sample  17011   1.913 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.621           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.677           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.428           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.560           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.855           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.855           ms/op
ClientSimple.listUser                       sample   9547   3.325 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.430           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.395           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.228           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.088           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.088           ms/op

Benchmark result is saved to 1725193007132.json
