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
# Warmup Iteration   1: 1.397 ops/ms
Iteration   1: 6.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.420 ops/ms


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
# Warmup Iteration   1: 5.962 ops/ms
Iteration   1: 13.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.118 ops/ms


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
# Warmup Iteration   1: 5.635 ops/ms
Iteration   1: 13.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.964 ops/ms


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
# Warmup Iteration   1: 4.528 ops/ms
Iteration   1: 9.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.074 ops/ms


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.087 ms/op
Iteration   1: 2.252 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.252 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.053 ms/op
Iteration   1: 2.197 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.197 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.073 ms/op
Iteration   1: 2.041 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.041 ms/op


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.094 ms/op
Iteration   1: 3.257 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.257 ms/op


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
# Warmup Iteration   1: 3.473 ±(99.9%) 0.092 ms/op
Iteration   1: 2.310 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.337 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  17.086 ms/op
                 createUser·p0.9999: 18.378 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13857
  mean =      2.310 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 306 
    [ 1.250,  2.500) = 9682 
    [ 2.500,  3.750) = 3472 
    [ 3.750,  5.000) = 271 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     17.086 ms/op
     p(99.9900) =     18.378 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.084 ms/op
Iteration   1: 2.049 ±(99.9%) 0.042 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  33.948 ms/op
                 existUser·p0.9999: 34.472 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15742
  mean =      2.049 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14169 
    [ 2.500,  5.000) = 1423 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =     33.948 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.088 ms/op
Iteration   1: 1.824 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   1.665 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.556 ms/op
                 getUser·p0.99:   3.242 ms/op
                 getUser·p0.999:  16.777 ms/op
                 getUser·p0.9999: 17.475 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17580
  mean =      1.824 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 614 
    [ 1.250,  2.500) = 15857 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.242 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     17.475 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.181 ms/op
Iteration   1: 3.570 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.338 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8880
  mean =      3.570 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 693 
    [ 2.500,  3.750) = 5208 
    [ 3.750,  5.000) = 2557 
    [ 5.000,  6.250) = 256 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.338 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.420          ops/ms
ClientSimple.existUser                       thrpt         13.118          ops/ms
ClientSimple.getUser                         thrpt         13.964          ops/ms
ClientSimple.listUser                        thrpt          9.074          ops/ms
ClientSimple.createUser                       avgt          2.252           ms/op
ClientSimple.existUser                        avgt          2.197           ms/op
ClientSimple.getUser                          avgt          2.041           ms/op
ClientSimple.listUser                         avgt          3.257           ms/op
ClientSimple.createUser                     sample  13857   2.310 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.337           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.776           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.086           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.378           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.416           ms/op
ClientSimple.existUser                      sample  15742   2.049 ± 0.042   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.736           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.891           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.948           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.472           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.472           ms/op
ClientSimple.getUser                        sample  17580   1.824 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.750           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.665           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.242           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.777           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.475           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.121           ms/op
ClientSimple.listUser                       sample   8880   3.570 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.323           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.338           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.615           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.302           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.302           ms/op

Benchmark result is saved to 1725797823481.json
