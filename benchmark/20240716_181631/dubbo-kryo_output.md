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
# Warmup Iteration   1: 1.315 ops/ms
Iteration   1: 6.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.147 ops/ms


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
# Warmup Iteration   1: 6.391 ops/ms
Iteration   1: 13.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.141 ops/ms


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
# Warmup Iteration   1: 5.355 ops/ms
Iteration   1: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.972 ops/ms


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
# Warmup Iteration   1: 4.667 ops/ms
Iteration   1: 8.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.812 ops/ms


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.075 ms/op
Iteration   1: 2.182 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.182 ms/op


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
# Warmup Iteration   1: 3.210 ±(99.9%) 0.057 ms/op
Iteration   1: 1.839 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.839 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.055 ms/op
Iteration   1: 2.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.098 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.113 ms/op
Iteration   1: 3.409 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.409 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.096 ms/op
Iteration   1: 2.057 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   1.845 ms/op
                 createUser·p0.90:   2.372 ms/op
                 createUser·p0.95:   2.576 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  33.620 ms/op
                 createUser·p0.9999: 33.969 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15560
  mean =      2.057 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14545 
    [ 2.500,  5.000) = 828 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     33.620 ms/op
     p(99.9900) =     33.969 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 2.681 ±(99.9%) 0.063 ms/op
Iteration   1: 2.086 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.765 ms/op
                 existUser·p0.95:   3.093 ms/op
                 existUser·p0.99:   3.861 ms/op
                 existUser·p0.999:  27.427 ms/op
                 existUser·p0.9999: 27.999 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15315
  mean =      2.086 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12893 
    [ 2.500,  5.000) = 2321 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.093 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =     27.427 ms/op
     p(99.9900) =     27.999 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.107 ms/op
Iteration   1: 2.005 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.523 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  18.778 ms/op
                 getUser·p0.9999: 19.676 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15942
  mean =      2.005 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 14170 
    [ 2.500,  3.750) = 1591 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =     18.778 ms/op
     p(99.9900) =     19.676 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.215 ms/op
Iteration   1: 4.010 ±(99.9%) 0.078 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.820 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.430 ms/op
                 listUser·p0.99:   8.227 ms/op
                 listUser·p0.999:  31.048 ms/op
                 listUser·p0.9999: 31.621 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8162
  mean =      4.010 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 414 
    [ 2.500,  5.000) = 7143 
    [ 5.000,  7.500) = 502 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.820 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.430 ms/op
     p(99.0000) =      8.227 ms/op
     p(99.9000) =     31.048 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.147          ops/ms
ClientSimple.existUser                       thrpt         13.141          ops/ms
ClientSimple.getUser                         thrpt         12.972          ops/ms
ClientSimple.listUser                        thrpt          8.812          ops/ms
ClientSimple.createUser                       avgt          2.182           ms/op
ClientSimple.existUser                        avgt          1.839           ms/op
ClientSimple.getUser                          avgt          2.098           ms/op
ClientSimple.listUser                         avgt          3.409           ms/op
ClientSimple.createUser                     sample  15560   2.057 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.608           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.845           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.372           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.718           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.620           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.969           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.079           ms/op
ClientSimple.existUser                      sample  15315   2.086 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.617           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.093           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.861           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.427           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.999           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.017           ms/op
ClientSimple.getUser                        sample  15942   2.005 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.969           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.609           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.778           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.676           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.890           ms/op
ClientSimple.listUser                       sample   8162   4.010 ± 0.078   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.901           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.820           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.430           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.227           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.048           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.621           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.621           ms/op

Benchmark result is saved to 1721153538774.json
