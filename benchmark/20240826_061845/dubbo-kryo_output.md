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
# Warmup Iteration   1: 2.050 ops/ms
Iteration   1: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.493 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.026 ops/ms
Iteration   1: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.175 ops/ms


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
# Warmup Iteration   1: 6.823 ops/ms
Iteration   1: 15.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.162 ops/ms


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
# Warmup Iteration   1: 4.908 ops/ms
Iteration   1: 8.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.416 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.079 ms/op
Iteration   1: 2.225 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.225 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ±(99.9%) 0.054 ms/op
Iteration   1: 1.858 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.858 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.072 ms/op
Iteration   1: 1.949 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.949 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.087 ms/op
Iteration   1: 3.140 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.140 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.442 ±(99.9%) 0.087 ms/op
Iteration   1: 2.210 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.888 ms/op
                 createUser·p0.99:   4.147 ms/op
                 createUser·p0.999:  41.057 ms/op
                 createUser·p0.9999: 46.996 ms/op
                 createUser·p1.00:   47.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14519
  mean =      2.210 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14417 
    [ 5.000, 10.000) = 6 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      4.147 ms/op
     p(99.9000) =     41.057 ms/op
     p(99.9900) =     46.996 ms/op
     p(99.9990) =     47.055 ms/op
     p(99.9999) =     47.055 ms/op
    p(100.0000) =     47.055 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ±(99.9%) 0.067 ms/op
Iteration   1: 2.047 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.897 ms/op
                 existUser·p0.999:  14.516 ms/op
                 existUser·p0.9999: 14.742 ms/op
                 existUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15621
  mean =      2.047 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 573 
    [ 1.250,  2.500) = 12895 
    [ 2.500,  3.750) = 1963 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.897 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     14.742 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.090 ms/op
Iteration   1: 2.049 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  15.794 ms/op
                 getUser·p0.9999: 19.017 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15615
  mean =      2.049 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 13403 
    [ 2.500,  3.750) = 1635 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     19.017 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.154 ms/op
Iteration   1: 3.724 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.526 ms/op
                 listUser·p0.999:  50.659 ms/op
                 listUser·p0.9999: 51.708 ms/op
                 listUser·p1.00:   51.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8610
  mean =      3.724 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8429 
    [ 5.000, 10.000) = 110 
    [10.000, 15.000) = 31 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.526 ms/op
     p(99.9000) =     50.659 ms/op
     p(99.9900) =     51.708 ms/op
     p(99.9990) =     51.708 ms/op
     p(99.9999) =     51.708 ms/op
    p(100.0000) =     51.708 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.493          ops/ms
ClientSimple.existUser                       thrpt         13.175          ops/ms
ClientSimple.getUser                         thrpt         15.162          ops/ms
ClientSimple.listUser                        thrpt          8.416          ops/ms
ClientSimple.createUser                       avgt          2.225           ms/op
ClientSimple.existUser                        avgt          1.858           ms/op
ClientSimple.getUser                          avgt          1.949           ms/op
ClientSimple.listUser                         avgt          3.140           ms/op
ClientSimple.createUser                     sample  14519   2.210 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.468           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.147           ms/op
ClientSimple.createUser:createUser·p0.999   sample         41.057           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         46.996           ms/op
ClientSimple.createUser:createUser·p1.00    sample         47.055           ms/op
ClientSimple.existUser                      sample  15621   2.047 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.577           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.897           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.516           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.742           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.778           ms/op
ClientSimple.getUser                        sample  15615   2.049 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.806           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.358           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.794           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.017           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.956           ms/op
ClientSimple.listUser                       sample   8610   3.724 ± 0.103   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.840           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.526           ms/op
ClientSimple.listUser:listUser·p0.999       sample         50.659           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         51.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         51.708           ms/op

Benchmark result is saved to 1724652863782.json
