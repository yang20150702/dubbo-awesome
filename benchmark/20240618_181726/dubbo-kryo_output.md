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
# Warmup Iteration   1: 1.767 ops/ms
Iteration   1: 6.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.033 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.726 ops/ms
Iteration   1: 13.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.382 ops/ms


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
# Warmup Iteration   1: 4.971 ops/ms
Iteration   1: 12.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.981 ops/ms


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
# Warmup Iteration   1: 4.759 ops/ms
Iteration   1: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.538 ops/ms


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.082 ms/op
Iteration   1: 2.271 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.271 ms/op


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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.073 ms/op
Iteration   1: 1.870 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.870 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.088 ms/op
Iteration   1: 2.407 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.407 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.087 ms/op
Iteration   1: 3.391 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.391 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.093 ms/op
Iteration   1: 2.042 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  15.155 ms/op
                 createUser·p0.9999: 15.981 ms/op
                 createUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15673
  mean =      2.042 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 14186 
    [ 2.500,  3.750) = 1099 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     15.981 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.063 ms/op
Iteration   1: 1.982 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   8.040 ms/op
                 existUser·p0.999:  20.112 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16225
  mean =      1.982 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14458 
    [ 2.500,  5.000) = 1478 
    [ 5.000,  7.500) = 127 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      8.040 ms/op
     p(99.9000) =     20.112 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.076 ms/op
Iteration   1: 2.138 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 17.515 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14994
  mean =      2.138 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 12535 
    [ 2.500,  3.750) = 2216 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.515 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.138 ms/op
Iteration   1: 3.402 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  7.043 ms/op
                 listUser·p0.9999: 7.520 ms/op
                 listUser·p1.00:   7.520 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9405
  mean =      3.402 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 74 
    [2.000, 2.500) = 1055 
    [2.500, 3.000) = 1920 
    [3.000, 3.500) = 1931 
    [3.500, 4.000) = 2845 
    [4.000, 4.500) = 985 
    [4.500, 5.000) = 253 
    [5.000, 5.500) = 173 
    [5.500, 6.000) = 79 
    [6.000, 6.500) = 22 
    [6.500, 7.000) = 44 
    [7.000, 7.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      7.043 ms/op
     p(99.9900) =      7.520 ms/op
     p(99.9990) =      7.520 ms/op
     p(99.9999) =      7.520 ms/op
    p(100.0000) =      7.520 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.033          ops/ms
ClientSimple.existUser                       thrpt         13.382          ops/ms
ClientSimple.getUser                         thrpt         12.981          ops/ms
ClientSimple.listUser                        thrpt          8.538          ops/ms
ClientSimple.createUser                       avgt          2.271           ms/op
ClientSimple.existUser                        avgt          1.870           ms/op
ClientSimple.getUser                          avgt          2.407           ms/op
ClientSimple.listUser                         avgt          3.391           ms/op
ClientSimple.createUser                     sample  15673   2.042 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.422           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.931           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.155           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.981           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.991           ms/op
ClientSimple.existUser                      sample  16225   1.982 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.539           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.99      sample          8.040           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.112           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.461           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.461           ms/op
ClientSimple.getUser                        sample  14994   2.138 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.813           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.166           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.302           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.515           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.531           ms/op
ClientSimple.listUser                       sample   9405   3.402 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.849           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.043           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.520           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.520           ms/op

Benchmark result is saved to 1718734371841.json
