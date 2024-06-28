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
# Warmup Iteration   1: 2.290 ops/ms
Iteration   1: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.105 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.421 ops/ms
Iteration   1: 15.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.057 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.721 ops/ms
Iteration   1: 14.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.461 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.466 ops/ms
Iteration   1: 8.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.700 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.650 ±(99.9%) 0.055 ms/op
Iteration   1: 2.012 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.012 ms/op


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
# Warmup Iteration   1: 2.876 ±(99.9%) 0.034 ms/op
Iteration   1: 1.865 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.865 ms/op


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
# Warmup Iteration   1: 2.811 ±(99.9%) 0.058 ms/op
Iteration   1: 1.841 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.067 ms/op
Iteration   1: 2.879 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.879 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.106 ms/op
Iteration   1: 2.015 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.425 ms/op
                 createUser·p0.95:   2.605 ms/op
                 createUser·p0.99:   7.416 ms/op
                 createUser·p0.999:  16.269 ms/op
                 createUser·p0.9999: 18.260 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15872
  mean =      2.015 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 603 
    [ 1.250,  2.500) = 14128 
    [ 2.500,  3.750) = 931 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      7.416 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     18.260 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ±(99.9%) 0.061 ms/op
Iteration   1: 2.170 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.058 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  46.465 ms/op
                 existUser·p0.9999: 47.084 ms/op
                 existUser·p1.00:   47.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15557
  mean =      2.170 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15473 
    [ 5.000, 10.000) = 20 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     46.465 ms/op
     p(99.9900) =     47.084 ms/op
     p(99.9990) =     47.120 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ±(99.9%) 0.072 ms/op
Iteration   1: 1.746 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   1.673 ms/op
                 getUser·p0.90:   2.083 ms/op
                 getUser·p0.95:   2.302 ms/op
                 getUser·p0.99:   2.896 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 12.828 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18439
  mean =      1.746 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 17523 
    [ 2.500,  3.750) = 353 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.083 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      2.896 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     12.828 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.099 ms/op
Iteration   1: 3.213 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.201 ms/op
                 listUser·p0.999:  16.631 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9952
  mean =      3.213 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1032 
    [ 2.500,  3.750) = 7299 
    [ 3.750,  5.000) = 1473 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.201 ms/op
     p(99.9000) =     16.631 ms/op
     p(99.9900) =     16.744 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.105          ops/ms
ClientSimple.existUser                       thrpt         15.057          ops/ms
ClientSimple.getUser                         thrpt         14.461          ops/ms
ClientSimple.listUser                        thrpt          8.700          ops/ms
ClientSimple.createUser                       avgt          2.012           ms/op
ClientSimple.existUser                        avgt          1.865           ms/op
ClientSimple.getUser                          avgt          1.841           ms/op
ClientSimple.listUser                         avgt          2.879           ms/op
ClientSimple.createUser                     sample  15872   2.015 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.379           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.416           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.269           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.260           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.317           ms/op
ClientSimple.existUser                      sample  15557   2.170 ± 0.054   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.595           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         46.465           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         47.084           ms/op
ClientSimple.existUser:existUser·p1.00      sample         47.120           ms/op
ClientSimple.getUser                        sample  18439   1.746 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.673           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.302           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.828           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.911           ms/op
ClientSimple.listUser                       sample   9952   3.213 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.953           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.985           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.201           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.631           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.744           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.744           ms/op

Benchmark result is saved to 1719598318975.json
