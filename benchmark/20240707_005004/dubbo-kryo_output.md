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
# Warmup Iteration   1: 1.826 ops/ms
Iteration   1: 7.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.536 ops/ms


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
# Warmup Iteration   1: 6.494 ops/ms
Iteration   1: 13.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.001 ops/ms


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
# Warmup Iteration   1: 5.292 ops/ms
Iteration   1: 14.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.067 ops/ms


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
# Warmup Iteration   1: 5.257 ops/ms
Iteration   1: 8.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.779 ops/ms


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.079 ms/op
Iteration   1: 2.055 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.055 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.059 ms/op
Iteration   1: 1.804 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.058 ms/op
Iteration   1: 2.230 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.230 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.076 ms/op
Iteration   1: 2.990 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.990 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.121 ms/op
Iteration   1: 2.004 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.376 ms/op
                 createUser·p0.95:   2.668 ms/op
                 createUser·p0.99:   4.516 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 17.492 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15953
  mean =      2.004 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 259 
    [ 1.250,  2.500) = 14551 
    [ 2.500,  3.750) = 870 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.668 ms/op
     p(99.0000) =      4.516 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     17.492 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 2.797 ±(99.9%) 0.067 ms/op
Iteration   1: 2.222 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.288 ms/op
                 existUser·p0.50:   2.142 ms/op
                 existUser·p0.90:   2.682 ms/op
                 existUser·p0.95:   2.945 ms/op
                 existUser·p0.99:   4.316 ms/op
                 existUser·p0.999:  18.799 ms/op
                 existUser·p0.9999: 21.106 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14411
  mean =      2.222 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11504 
    [ 2.500,  5.000) = 2805 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.682 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      4.316 ms/op
     p(99.9000) =     18.799 ms/op
     p(99.9900) =     21.106 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.076 ms/op
Iteration   1: 1.705 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   1.583 ms/op
                 getUser·p0.90:   2.347 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   2.911 ms/op
                 getUser·p0.999:  6.489 ms/op
                 getUser·p0.9999: 6.604 ms/op
                 getUser·p1.00:   6.619 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18937
  mean =      1.705 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 108 
    [1.000, 1.500) = 8121 
    [1.500, 2.000) = 6274 
    [2.000, 2.500) = 3164 
    [2.500, 3.000) = 1104 
    [3.000, 3.500) = 79 
    [3.500, 4.000) = 31 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.583 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      2.911 ms/op
     p(99.9000) =      6.489 ms/op
     p(99.9900) =      6.604 ms/op
     p(99.9990) =      6.619 ms/op
     p(99.9999) =      6.619 ms/op
    p(100.0000) =      6.619 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.167 ms/op
Iteration   1: 3.298 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.269 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.160 ms/op
                 listUser·p0.99:   5.062 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9705
  mean =      3.298 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1037 
    [ 2.500,  3.750) = 6236 
    [ 3.750,  5.000) = 2332 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.160 ms/op
     p(99.0000) =      5.062 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.536          ops/ms
ClientSimple.existUser                       thrpt         13.001          ops/ms
ClientSimple.getUser                         thrpt         14.067          ops/ms
ClientSimple.listUser                        thrpt          8.779          ops/ms
ClientSimple.createUser                       avgt          2.055           ms/op
ClientSimple.existUser                        avgt          1.804           ms/op
ClientSimple.getUser                          avgt          2.230           ms/op
ClientSimple.listUser                         avgt          2.990           ms/op
ClientSimple.createUser                     sample  15953   2.004 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.376           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.668           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.516           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.492           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.531           ms/op
ClientSimple.existUser                      sample  14411   2.222 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.288           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.142           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.682           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.945           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.316           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.799           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.106           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.135           ms/op
ClientSimple.getUser                        sample  18937   1.705 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.583           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.911           ms/op
ClientSimple.getUser:getUser·p0.999         sample          6.489           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          6.604           ms/op
ClientSimple.getUser:getUser·p1.00          sample          6.619           ms/op
ClientSimple.listUser                       sample   9705   3.298 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.194           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.269           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.002           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.160           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.062           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.759           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.857           ms/op

Benchmark result is saved to 1720313150246.json
