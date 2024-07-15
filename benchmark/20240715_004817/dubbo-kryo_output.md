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
# Warmup Iteration   1: 0.747 ops/ms
Iteration   1: 5.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.470 ops/ms


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
# Warmup Iteration   1: 5.566 ops/ms
Iteration   1: 13.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.395 ops/ms


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
# Warmup Iteration   1: 5.522 ops/ms
Iteration   1: 11.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.282 ops/ms


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
# Warmup Iteration   1: 4.240 ops/ms
Iteration   1: 8.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.272 ops/ms


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.062 ms/op
Iteration   1: 2.242 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


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
# Warmup Iteration   1: 3.406 ±(99.9%) 0.058 ms/op
Iteration   1: 1.862 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.056 ms/op
Iteration   1: 1.847 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.847 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.096 ms/op
Iteration   1: 3.497 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.497 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.087 ms/op
Iteration   1: 2.063 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   1.831 ms/op
                 createUser·p0.90:   2.355 ms/op
                 createUser·p0.95:   2.544 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  33.407 ms/op
                 createUser·p0.9999: 33.941 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15500
  mean =      2.063 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14650 
    [ 2.500,  5.000) = 548 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     33.407 ms/op
     p(99.9900) =     33.941 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 2.753 ±(99.9%) 0.064 ms/op
Iteration   1: 1.914 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.605 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   4.220 ms/op
                 existUser·p0.999:  23.822 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16586
  mean =      1.914 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14738 
    [ 2.500,  5.000) = 1749 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      4.220 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.096 ms/op
Iteration   1: 2.314 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.232 ms/op
                 getUser·p0.90:   2.855 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   4.660 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 18.942 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13816
  mean =      2.314 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 10212 
    [ 2.500,  3.750) = 3324 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      4.660 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     18.942 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 4.996 ±(99.9%) 0.289 ms/op
Iteration   1: 3.522 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.379 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  17.888 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9086
  mean =      3.522 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 402 
    [ 2.500,  3.750) = 5632 
    [ 3.750,  5.000) = 2734 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     17.888 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.470          ops/ms
ClientSimple.existUser                       thrpt         13.395          ops/ms
ClientSimple.getUser                         thrpt         11.282          ops/ms
ClientSimple.listUser                        thrpt          8.272          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          1.847           ms/op
ClientSimple.listUser                         avgt          3.497           ms/op
ClientSimple.createUser                     sample  15500   2.063 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.502           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.831           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.355           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.535           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.407           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.013           ms/op
ClientSimple.existUser                      sample  16586   1.914 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.220           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.822           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.642           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.707           ms/op
ClientSimple.getUser                        sample  13816   2.314 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.866           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.232           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.660           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.891           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.942           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.268           ms/op
ClientSimple.listUser                       sample   9086   3.522 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.379           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.995           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.888           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.383           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.383           ms/op

Benchmark result is saved to 1721004234449.json
