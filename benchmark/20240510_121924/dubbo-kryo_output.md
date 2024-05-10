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
# Warmup Iteration   1: 0.769 ops/ms
Iteration   1: 6.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.039 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.623 ops/ms
Iteration   1: 12.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.177 ops/ms


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
# Warmup Iteration   1: 6.744 ops/ms
Iteration   1: 13.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.346 ops/ms


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
# Warmup Iteration   1: 3.338 ops/ms
Iteration   1: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.082 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.088 ms/op
Iteration   1: 2.327 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.327 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.060 ms/op
Iteration   1: 1.895 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.055 ms/op
Iteration   1: 2.043 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.043 ms/op


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
# Warmup Iteration   1: 5.380 ±(99.9%) 0.146 ms/op
Iteration   1: 3.714 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.714 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.089 ms/op
Iteration   1: 2.057 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.465 ms/op
                 createUser·p0.50:   1.796 ms/op
                 createUser·p0.90:   2.236 ms/op
                 createUser·p0.95:   2.482 ms/op
                 createUser·p0.99:   9.847 ms/op
                 createUser·p0.999:  34.959 ms/op
                 createUser·p0.9999: 37.756 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15786
  mean =      2.057 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15022 
    [ 2.500,  5.000) = 497 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     34.959 ms/op
     p(99.9900) =     37.756 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.066 ms/op
Iteration   1: 1.836 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.853 ms/op
                 existUser·p0.999:  12.410 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17538
  mean =      1.836 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 425 
    [ 1.250,  2.500) = 16367 
    [ 2.500,  3.750) = 566 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.853 ms/op
     p(99.9000) =     12.410 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 3.571 ±(99.9%) 0.088 ms/op
Iteration   1: 2.096 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.908 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 10.592 ms/op
                 getUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15393
  mean =      2.096 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 51 
    [ 1.000,  2.000) = 8175 
    [ 2.000,  3.000) = 6032 
    [ 3.000,  4.000) = 937 
    [ 4.000,  5.000) = 106 
    [ 5.000,  6.000) = 25 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 10 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     10.592 ms/op
     p(99.9990) =     10.600 ms/op
     p(99.9999) =     10.600 ms/op
    p(100.0000) =     10.600 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.149 ms/op
Iteration   1: 3.719 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8586
  mean =      3.719 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 727 
    [ 2.500,  5.000) = 7547 
    [ 5.000,  7.500) = 237 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.039          ops/ms
ClientSimple.existUser                       thrpt         12.177          ops/ms
ClientSimple.getUser                         thrpt         13.346          ops/ms
ClientSimple.listUser                        thrpt          8.082          ops/ms
ClientSimple.createUser                       avgt          2.327           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.043           ms/op
ClientSimple.listUser                         avgt          3.714           ms/op
ClientSimple.createUser                     sample  15786   2.057 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.465           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.796           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.236           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.482           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.847           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.959           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.756           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.945           ms/op
ClientSimple.existUser                      sample  17538   1.836 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.444           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.853           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.410           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.025           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.124           ms/op
ClientSimple.getUser                        sample  15393   2.096 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.781           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.604           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.469           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.592           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.600           ms/op
ClientSimple.listUser                       sample   8586   3.719 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.233           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.666           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.101           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.233           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.233           ms/op

Benchmark result is saved to 1715343305429.json
