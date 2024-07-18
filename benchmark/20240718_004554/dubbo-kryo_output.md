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
# Warmup Iteration   1: 1.930 ops/ms
Iteration   1: 7.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.543 ops/ms


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
# Warmup Iteration   1: 5.901 ops/ms
Iteration   1: 12.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.032 ops/ms


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
# Warmup Iteration   1: 6.039 ops/ms
Iteration   1: 13.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.578 ops/ms


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
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 8.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.908 ops/ms


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.062 ms/op
Iteration   1: 1.933 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.933 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.047 ms/op
Iteration   1: 1.841 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.841 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.048 ms/op
Iteration   1: 1.911 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.911 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.069 ms/op
Iteration   1: 3.396 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.396 ms/op


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
# Warmup Iteration   1: 3.325 ±(99.9%) 0.082 ms/op
Iteration   1: 2.330 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.103 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 17.805 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13747
  mean =      2.330 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 10992 
    [ 2.500,  3.750) = 2256 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.103 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.805 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 2.929 ±(99.9%) 0.075 ms/op
Iteration   1: 1.864 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  10.370 ms/op
                 existUser·p0.9999: 11.113 ms/op
                 existUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17210
  mean =      1.864 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 276 
    [ 1.250,  2.500) = 16264 
    [ 2.500,  3.750) = 595 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     10.370 ms/op
     p(99.9900) =     11.113 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.082 ms/op
Iteration   1: 2.450 ±(99.9%) 0.084 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.083 ms/op
                 getUser·p0.90:   2.793 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   7.749 ms/op
                 getUser·p0.999:  43.778 ms/op
                 getUser·p0.9999: 44.492 ms/op
                 getUser·p1.00:   44.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13010
  mean =      2.450 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12673 
    [ 5.000, 10.000) = 227 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      7.749 ms/op
     p(99.9000) =     43.778 ms/op
     p(99.9900) =     44.492 ms/op
     p(99.9990) =     44.630 ms/op
     p(99.9999) =     44.630 ms/op
    p(100.0000) =     44.630 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.141 ms/op
Iteration   1: 3.720 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  6.675 ms/op
                 listUser·p0.9999: 6.914 ms/op
                 listUser·p1.00:   6.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8589
  mean =      3.720 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 135 
    [2.000, 2.500) = 770 
    [2.500, 3.000) = 1138 
    [3.000, 3.500) = 1277 
    [3.500, 4.000) = 1826 
    [4.000, 4.500) = 1676 
    [4.500, 5.000) = 1162 
    [5.000, 5.500) = 449 
    [5.500, 6.000) = 103 
    [6.000, 6.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      6.675 ms/op
     p(99.9900) =      6.914 ms/op
     p(99.9990) =      6.914 ms/op
     p(99.9999) =      6.914 ms/op
    p(100.0000) =      6.914 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.543          ops/ms
ClientSimple.existUser                       thrpt         12.032          ops/ms
ClientSimple.getUser                         thrpt         13.578          ops/ms
ClientSimple.listUser                        thrpt          8.908          ops/ms
ClientSimple.createUser                       avgt          1.933           ms/op
ClientSimple.existUser                        avgt          1.841           ms/op
ClientSimple.getUser                          avgt          1.911           ms/op
ClientSimple.listUser                         avgt          3.396           ms/op
ClientSimple.createUser                     sample  13747   2.330 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.808           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.103           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.503           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.805           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.891           ms/op
ClientSimple.existUser                      sample  17210   1.864 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.567           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.792           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.178           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.370           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.113           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.125           ms/op
ClientSimple.getUser                        sample  13010   2.450 ± 0.084   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.265           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.749           ms/op
ClientSimple.getUser:getUser·p0.999         sample         43.778           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         44.492           ms/op
ClientSimple.getUser:getUser·p1.00          sample         44.630           ms/op
ClientSimple.listUser                       sample   8589   3.720 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.947           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.793           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.891           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.095           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.661           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.675           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.914           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.914           ms/op

Benchmark result is saved to 1721263314127.json
