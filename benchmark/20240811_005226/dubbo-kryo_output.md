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
# Warmup Iteration   1: 1.496 ops/ms
Iteration   1: 6.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.714 ops/ms


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
# Warmup Iteration   1: 5.202 ops/ms
Iteration   1: 11.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.454 ops/ms


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
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 11.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.359 ops/ms


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
# Warmup Iteration   1: 5.158 ops/ms
Iteration   1: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.365 ops/ms


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.082 ms/op
Iteration   1: 2.079 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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
# Warmup Iteration   1: 3.039 ±(99.9%) 0.044 ms/op
Iteration   1: 1.771 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.771 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.086 ms/op
Iteration   1: 2.100 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.100 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.085 ms/op
Iteration   1: 3.501 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.501 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.107 ms/op
Iteration   1: 2.404 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  19.365 ms/op
                 createUser·p0.9999: 22.785 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13308
  mean =      2.404 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9504 
    [ 2.500,  5.000) = 3607 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     19.365 ms/op
     p(99.9900) =     22.785 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.077 ms/op
Iteration   1: 1.916 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  19.571 ms/op
                 existUser·p0.9999: 19.671 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16740
  mean =      1.916 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 14838 
    [ 2.500,  3.750) = 1611 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =     19.571 ms/op
     p(99.9900) =     19.671 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.080 ms/op
Iteration   1: 2.110 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   2.093 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  14.202 ms/op
                 getUser·p0.9999: 15.256 ms/op
                 getUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15153
  mean =      2.110 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 523 
    [ 1.250,  2.500) = 12538 
    [ 2.500,  3.750) = 1867 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     14.202 ms/op
     p(99.9900) =     15.256 ms/op
     p(99.9990) =     15.450 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.152 ms/op
Iteration   1: 3.521 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  31.679 ms/op
                 listUser·p0.9999: 32.276 ms/op
                 listUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9087
  mean =      3.521 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 448 
    [ 2.500,  5.000) = 8309 
    [ 5.000,  7.500) = 265 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     31.679 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.714          ops/ms
ClientSimple.existUser                       thrpt         11.454          ops/ms
ClientSimple.getUser                         thrpt         11.359          ops/ms
ClientSimple.listUser                        thrpt          8.365          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          1.771           ms/op
ClientSimple.getUser                          avgt          2.100           ms/op
ClientSimple.listUser                         avgt          3.501           ms/op
ClientSimple.createUser                     sample  13308   2.404 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.931           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.355           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.571           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.365           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.785           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.807           ms/op
ClientSimple.existUser                      sample  16740   1.916 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.652           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.789           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.736           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.571           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.671           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.694           ms/op
ClientSimple.getUser                        sample  15153   2.110 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.639           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.093           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.227           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.202           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.256           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.450           ms/op
ClientSimple.listUser                       sample   9087   3.521 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.260           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.053           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.679           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.276           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.276           ms/op

Benchmark result is saved to 1723337277841.json
