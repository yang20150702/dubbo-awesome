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
# Warmup Iteration   1: 1.727 ops/ms
Iteration   1: 7.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.446 ops/ms


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
# Warmup Iteration   1: 6.233 ops/ms
Iteration   1: 13.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.580 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 13.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.577 ops/ms


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
# Warmup Iteration   1: 4.302 ops/ms
Iteration   1: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.442 ops/ms


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.093 ms/op
Iteration   1: 2.188 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.188 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.049 ms/op
Iteration   1: 1.770 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.770 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.070 ms/op
Iteration   1: 1.998 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.998 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.092 ms/op
Iteration   1: 3.144 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.144 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.075 ms/op
Iteration   1: 2.125 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   5.567 ms/op
                 createUser·p0.999:  26.411 ms/op
                 createUser·p0.9999: 30.228 ms/op
                 createUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15039
  mean =      2.125 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13052 
    [ 2.500,  5.000) = 1798 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.567 ms/op
     p(99.9000) =     26.411 ms/op
     p(99.9900) =     30.228 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.071 ms/op
Iteration   1: 1.965 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   1.903 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.397 ms/op
                 existUser·p0.999:  14.479 ms/op
                 existUser·p0.9999: 14.618 ms/op
                 existUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16268
  mean =      1.965 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 883 
    [ 1.250,  2.500) = 14225 
    [ 2.500,  3.750) = 1009 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.397 ms/op
     p(99.9000) =     14.479 ms/op
     p(99.9900) =     14.618 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.079 ms/op
Iteration   1: 2.045 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   3.355 ms/op
                 getUser·p0.999:  4.227 ms/op
                 getUser·p0.9999: 5.387 ms/op
                 getUser·p1.00:   5.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15640
  mean =      2.045 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 16 
    [1.000, 1.500) = 836 
    [1.500, 2.000) = 8328 
    [2.000, 2.500) = 3975 
    [2.500, 3.000) = 2140 
    [3.000, 3.500) = 211 
    [3.500, 4.000) = 45 
    [4.000, 4.500) = 86 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.355 ms/op
     p(99.9000) =      4.227 ms/op
     p(99.9900) =      5.387 ms/op
     p(99.9990) =      5.669 ms/op
     p(99.9999) =      5.669 ms/op
    p(100.0000) =      5.669 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.130 ms/op
Iteration   1: 3.292 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.347 ms/op
                 listUser·p0.999:  6.144 ms/op
                 listUser·p0.9999: 8.602 ms/op
                 listUser·p1.00:   8.602 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9729
  mean =      3.292 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 41 
    [2.000, 2.500) = 236 
    [2.500, 3.000) = 3956 
    [3.000, 3.500) = 2446 
    [3.500, 4.000) = 1619 
    [4.000, 4.500) = 1061 
    [4.500, 5.000) = 218 
    [5.000, 5.500) = 73 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.347 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =      8.602 ms/op
     p(99.9990) =      8.602 ms/op
     p(99.9999) =      8.602 ms/op
    p(100.0000) =      8.602 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.446          ops/ms
ClientSimple.existUser                       thrpt         13.580          ops/ms
ClientSimple.getUser                         thrpt         13.577          ops/ms
ClientSimple.listUser                        thrpt          8.442          ops/ms
ClientSimple.createUser                       avgt          2.188           ms/op
ClientSimple.existUser                        avgt          1.770           ms/op
ClientSimple.getUser                          avgt          1.998           ms/op
ClientSimple.listUser                         avgt          3.144           ms/op
ClientSimple.createUser                     sample  15039   2.125 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.773           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.567           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.411           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.228           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.245           ms/op
ClientSimple.existUser                      sample  16268   1.965 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.764           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.903           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.397           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.479           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.618           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.680           ms/op
ClientSimple.getUser                        sample  15640   2.045 ± 0.011   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.755           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.355           ms/op
ClientSimple.getUser:getUser·p0.999         sample          4.227           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          5.387           ms/op
ClientSimple.getUser:getUser·p1.00          sample          5.669           ms/op
ClientSimple.listUser                       sample   9729   3.292 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.079           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.347           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.144           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.602           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.602           ms/op

Benchmark result is saved to 1725473570266.json
