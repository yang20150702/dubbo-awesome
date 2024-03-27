# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.628 ops/ms
Iteration   1: 6.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.367 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.931 ops/ms
Iteration   1: 12.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.716 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.577 ops/ms
Iteration   1: 13.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.131 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ops/ms
Iteration   1: 9.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.189 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.068 ms/op
Iteration   1: 2.085 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.085 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ±(99.9%) 0.058 ms/op
Iteration   1: 2.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.016 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.318 ±(99.9%) 0.062 ms/op
Iteration   1: 2.159 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.159 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.083 ms/op
Iteration   1: 3.283 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.283 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ±(99.9%) 0.095 ms/op
Iteration   1: 2.123 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   10.261 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15072
  mean =      2.123 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13531 
    [ 2.500,  5.000) = 1244 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =     10.261 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.288 ±(99.9%) 0.077 ms/op
Iteration   1: 1.922 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.426 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 11.195 ms/op
                 existUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16676
  mean =      1.922 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 15174 
    [ 2.500,  3.750) = 1017 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.426 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     11.195 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.093 ms/op
Iteration   1: 2.033 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.270 ms/op
                 getUser·p0.50:   1.841 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   4.804 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 20.653 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15758
  mean =      2.033 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13997 
    [ 2.500,  5.000) = 1648 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.270 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.804 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     20.653 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ±(99.9%) 0.147 ms/op
Iteration   1: 3.329 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.389 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  11.524 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9601
  mean =      3.329 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1194 
    [ 2.500,  3.750) = 5647 
    [ 3.750,  5.000) = 2523 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      4.389 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     11.524 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     11.616 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.367          ops/ms
ClientSimple.existUser                       thrpt         12.716          ops/ms
ClientSimple.getUser                         thrpt         13.131          ops/ms
ClientSimple.listUser                        thrpt          9.189          ops/ms
ClientSimple.createUser                       avgt          2.085           ms/op
ClientSimple.existUser                        avgt          2.016           ms/op
ClientSimple.getUser                          avgt          2.159           ms/op
ClientSimple.listUser                         avgt          3.283           ms/op
ClientSimple.createUser                     sample  15072   2.123 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.261           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.530           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.447           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  16676   1.922 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.593           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.426           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.497           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.584           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.195           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.502           ms/op
ClientSimple.getUser                        sample  15758   2.033 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.270           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.841           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.804           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.513           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.653           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.709           ms/op
ClientSimple.listUser                       sample   9601   3.329 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.253           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.064           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.389           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.890           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.524           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.616           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.616           ms/op

Benchmark result is saved to 1711519887299.json
