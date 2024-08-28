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
# Warmup Iteration   1: 1.563 ops/ms
Iteration   1: 6.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.901 ops/ms


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
# Warmup Iteration   1: 5.265 ops/ms
Iteration   1: 13.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.490 ops/ms


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
# Warmup Iteration   1: 5.257 ops/ms
Iteration   1: 13.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.163 ops/ms


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
# Warmup Iteration   1: 5.051 ops/ms
Iteration   1: 8.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.853 ops/ms


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.076 ms/op
Iteration   1: 2.068 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.055 ms/op
Iteration   1: 1.884 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.053 ms/op
Iteration   1: 2.219 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.219 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.083 ms/op
Iteration   1: 3.336 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.336 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.125 ms/op
Iteration   1: 2.218 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  15.142 ms/op
                 createUser·p0.9999: 15.328 ms/op
                 createUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14410
  mean =      2.218 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 12040 
    [ 2.500,  3.750) = 1908 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     15.142 ms/op
     p(99.9900) =     15.328 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.062 ms/op
Iteration   1: 2.141 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.988 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  34.275 ms/op
                 existUser·p0.9999: 34.406 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14987
  mean =      2.141 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12647 
    [ 2.500,  5.000) = 2160 
    [ 5.000,  7.500) = 84 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.988 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     34.275 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.096 ms/op
Iteration   1: 2.076 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   4.587 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 11.160 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15401
  mean =      2.076 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 13350 
    [ 2.500,  3.750) = 1710 
    [ 3.750,  5.000) = 171 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.587 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     11.160 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.335 ms/op
Iteration   1: 3.491 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.128 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 14.860 ms/op
                 listUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9157
  mean =      3.491 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 424 
    [ 2.500,  3.750) = 5452 
    [ 3.750,  5.000) = 3106 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     14.326 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.901          ops/ms
ClientSimple.existUser                       thrpt         13.490          ops/ms
ClientSimple.getUser                         thrpt         13.163          ops/ms
ClientSimple.listUser                        thrpt          8.853          ops/ms
ClientSimple.createUser                       avgt          2.068           ms/op
ClientSimple.existUser                        avgt          1.884           ms/op
ClientSimple.getUser                          avgt          2.219           ms/op
ClientSimple.listUser                         avgt          3.336           ms/op
ClientSimple.createUser                     sample  14410   2.218 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.160           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.142           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.328           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.335           ms/op
ClientSimple.existUser                      sample  14987   2.141 ± 0.053   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.448           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.988           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.980           ms/op
ClientSimple.existUser:existUser·p0.999     sample         34.275           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.406           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.406           ms/op
ClientSimple.getUser                        sample  15401   2.076 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.807           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.587           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.977           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.160           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.239           ms/op
ClientSimple.listUser                       sample   9157   3.491 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.083           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.441           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.128           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.326           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.860           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.860           ms/op

Benchmark result is saved to 1724868783281.json
