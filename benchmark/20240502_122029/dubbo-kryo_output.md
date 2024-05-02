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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 7.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.662 ops/ms


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
# Warmup Iteration   1: 6.759 ops/ms
Iteration   1: 10.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.972 ops/ms


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
# Warmup Iteration   1: 4.851 ops/ms
Iteration   1: 14.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.269 ops/ms


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
# Warmup Iteration   1: 5.615 ops/ms
Iteration   1: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.487 ops/ms


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.065 ms/op
Iteration   1: 2.156 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.156 ms/op


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
# Warmup Iteration   1: 4.808 ±(99.9%) 0.102 ms/op
Iteration   1: 2.145 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.145 ms/op


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
# Warmup Iteration   1: 3.418 ±(99.9%) 0.057 ms/op
Iteration   1: 2.145 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.145 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.078 ms/op
Iteration   1: 3.226 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.226 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.108 ms/op
Iteration   1: 2.639 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.475 ms/op
                 createUser·p0.50:   2.359 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   12.517 ms/op
                 createUser·p0.999:  14.189 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12295
  mean =      2.639 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 7141 
    [ 2.500,  3.750) = 4385 
    [ 3.750,  5.000) = 299 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =     12.517 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.076 ms/op
Iteration   1: 1.718 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   1.481 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.271 ms/op
                 existUser·p0.999:  29.983 ms/op
                 existUser·p0.9999: 30.502 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18603
  mean =      1.718 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17539 
    [ 2.500,  5.000) = 934 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.481 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.271 ms/op
     p(99.9000) =     29.983 ms/op
     p(99.9900) =     30.502 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.073 ms/op
Iteration   1: 1.942 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   1.724 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  14.705 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16462
  mean =      1.942 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 309 
    [ 1.250,  2.500) = 14065 
    [ 2.500,  3.750) = 1935 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =     14.705 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.139 ms/op
Iteration   1: 3.239 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.207 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.119 ms/op
                 listUser·p0.999:  11.831 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9905
  mean =      3.239 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1593 
    [ 2.500,  3.750) = 6331 
    [ 3.750,  5.000) = 1716 
    [ 5.000,  6.250) = 186 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     11.831 ms/op
     p(99.9900) =     11.993 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.662          ops/ms
ClientSimple.existUser                       thrpt         10.972          ops/ms
ClientSimple.getUser                         thrpt         14.269          ops/ms
ClientSimple.listUser                        thrpt          8.487          ops/ms
ClientSimple.createUser                       avgt          2.156           ms/op
ClientSimple.existUser                        avgt          2.145           ms/op
ClientSimple.getUser                          avgt          2.145           ms/op
ClientSimple.listUser                         avgt          3.226           ms/op
ClientSimple.createUser                     sample  12295   2.639 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.475           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.359           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.760           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.517           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.189           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.089           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.089           ms/op
ClientSimple.existUser                      sample  18603   1.718 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.578           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.481           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.271           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.983           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.671           ms/op
ClientSimple.getUser                        sample  16462   1.942 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.745           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.724           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.715           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.705           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.008           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.008           ms/op
ClientSimple.listUser                       sample   9905   3.239 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.997           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.207           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.119           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.831           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.993           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.993           ms/op

Benchmark result is saved to 1714652140556.json
