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
# Warmup Iteration   1: 0.926 ops/ms
Iteration   1: 5.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.264 ops/ms


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
# Warmup Iteration   1: 5.023 ops/ms
Iteration   1: 11.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.853 ops/ms


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
# Warmup Iteration   1: 6.119 ops/ms
Iteration   1: 11.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.658 ops/ms


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
# Warmup Iteration   1: 4.934 ops/ms
Iteration   1: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.464 ops/ms


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.075 ms/op
Iteration   1: 2.355 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.355 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.047 ms/op
Iteration   1: 1.974 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.062 ms/op
Iteration   1: 2.309 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.309 ms/op


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.091 ms/op
Iteration   1: 3.514 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.514 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.084 ms/op
Iteration   1: 2.203 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  20.234 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14506
  mean =      2.203 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12252 
    [ 2.500,  5.000) = 1944 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     20.234 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.087 ms/op
Iteration   1: 2.075 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   1.921 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.773 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  24.543 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15410
  mean =      2.075 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13645 
    [ 2.500,  5.000) = 1576 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.111 ms/op
Iteration   1: 2.241 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.175 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   4.151 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 13.450 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14267
  mean =      2.241 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 11407 
    [ 2.500,  3.750) = 2563 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      4.151 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     13.450 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 5.489 ±(99.9%) 0.179 ms/op
Iteration   1: 3.794 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  15.552 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8434
  mean =      3.794 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 665 
    [ 2.500,  3.750) = 3380 
    [ 3.750,  5.000) = 4030 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     15.552 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.264          ops/ms
ClientSimple.existUser                       thrpt         11.853          ops/ms
ClientSimple.getUser                         thrpt         11.658          ops/ms
ClientSimple.listUser                        thrpt          8.464          ops/ms
ClientSimple.createUser                       avgt          2.355           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.309           ms/op
ClientSimple.listUser                         avgt          3.514           ms/op
ClientSimple.createUser                     sample  14506   2.203 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.778           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.600           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.234           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.611           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.611           ms/op
ClientSimple.existUser                      sample  15410   2.075 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.867           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.921           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.773           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.267           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.543           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.642           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.642           ms/op
ClientSimple.getUser                        sample  14267   2.241 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.691           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.175           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.151           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.272           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.450           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.730           ms/op
ClientSimple.listUser                       sample   8434   3.794 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.593           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.633           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.552           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.908           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.908           ms/op

Benchmark result is saved to 1718777578811.json
