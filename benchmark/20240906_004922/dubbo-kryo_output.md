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
# Warmup Iteration   1: 1.279 ops/ms
Iteration   1: 6.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.961 ops/ms


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
# Warmup Iteration   1: 6.194 ops/ms
Iteration   1: 12.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.595 ops/ms


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
# Warmup Iteration   1: 5.299 ops/ms
Iteration   1: 12.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.365 ops/ms


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
# Warmup Iteration   1: 4.579 ops/ms
Iteration   1: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.073 ops/ms


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.061 ms/op
Iteration   1: 2.355 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.355 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.064 ms/op
Iteration   1: 1.926 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.080 ms/op
Iteration   1: 2.078 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.078 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.102 ms/op
Iteration   1: 3.119 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.119 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.110 ms/op
Iteration   1: 2.495 ±(99.9%) 0.120 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.171 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   10.897 ms/op
                 createUser·p0.999:  82.336 ms/op
                 createUser·p0.9999: 92.349 ms/op
                 createUser·p1.00:   95.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12822
  mean =      2.495 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 12694 
    [ 10.000,  20.000) = 96 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =     10.897 ms/op
     p(99.9000) =     82.336 ms/op
     p(99.9900) =     92.349 ms/op
     p(99.9990) =     95.420 ms/op
     p(99.9999) =     95.420 ms/op
    p(100.0000) =     95.420 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.079 ms/op
Iteration   1: 1.804 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.307 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 14.421 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18552
  mean =      1.804 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 17236 
    [ 2.500,  3.750) = 993 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.307 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     14.421 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.143 ms/op
Iteration   1: 2.347 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.183 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.445 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 14.514 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13642
  mean =      2.347 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 9439 
    [ 2.500,  3.750) = 3657 
    [ 3.750,  5.000) = 258 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     14.514 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.162 ms/op
Iteration   1: 3.644 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.450 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.327 ms/op
                 listUser·p0.9999: 13.468 ms/op
                 listUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8805
  mean =      3.644 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 1052 
    [ 2.500,  3.750) = 3656 
    [ 3.750,  5.000) = 3658 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     13.327 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.961          ops/ms
ClientSimple.existUser                       thrpt         12.595          ops/ms
ClientSimple.getUser                         thrpt         12.365          ops/ms
ClientSimple.listUser                        thrpt          8.073          ops/ms
ClientSimple.createUser                       avgt          2.355           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          2.078           ms/op
ClientSimple.listUser                         avgt          3.119           ms/op
ClientSimple.createUser                     sample  12822   2.495 ± 0.120   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.581           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.171           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.897           ms/op
ClientSimple.createUser:createUser·p0.999   sample         82.336           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         92.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         95.420           ms/op
ClientSimple.existUser                      sample  18552   1.804 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.398           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.307           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.844           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.421           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.533           ms/op
ClientSimple.getUser                        sample  13642   2.347 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.628           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.162           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.445           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.784           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.533           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.514           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.926           ms/op
ClientSimple.listUser                       sample   8805   3.644 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.450           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.678           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.193           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.327           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.468           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.468           ms/op

Benchmark result is saved to 1725583533329.json
