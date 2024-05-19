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
# Warmup Iteration   1: 1.652 ops/ms
Iteration   1: 6.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.340 ops/ms


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
# Warmup Iteration   1: 6.133 ops/ms
Iteration   1: 11.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.611 ops/ms


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
# Warmup Iteration   1: 6.310 ops/ms
Iteration   1: 12.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.279 ops/ms


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
# Warmup Iteration   1: 4.454 ops/ms
Iteration   1: 7.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.714 ops/ms


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.071 ms/op
Iteration   1: 2.463 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.463 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.045 ms/op
Iteration   1: 1.779 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.779 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.059 ms/op
Iteration   1: 2.207 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.207 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.211 ms/op
Iteration   1: 3.524 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.524 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.080 ms/op
Iteration   1: 2.119 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.392 ms/op
                 createUser·p0.95:   2.619 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  16.724 ms/op
                 createUser·p0.9999: 17.171 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15249
  mean =      2.119 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 14071 
    [ 2.500,  3.750) = 860 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.619 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     16.724 ms/op
     p(99.9900) =     17.171 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.085 ms/op
Iteration   1: 1.969 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   5.134 ms/op
                 existUser·p0.999:  57.082 ms/op
                 existUser·p0.9999: 57.958 ms/op
                 existUser·p1.00:   57.999 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16234
  mean =      1.969 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16071 
    [ 5.000, 10.000) = 90 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      5.134 ms/op
     p(99.9000) =     57.082 ms/op
     p(99.9900) =     57.958 ms/op
     p(99.9990) =     57.999 ms/op
     p(99.9999) =     57.999 ms/op
    p(100.0000) =     57.999 ms/op


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
# Warmup Iteration   1: 3.008 ±(99.9%) 0.077 ms/op
Iteration   1: 2.202 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.066 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   3.950 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14585
  mean =      2.202 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11593 
    [ 2.500,  5.000) = 2910 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      3.950 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.169 ms/op
Iteration   1: 3.174 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.277 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 16.721 ms/op
                 listUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10081
  mean =      3.174 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1078 
    [ 2.500,  3.750) = 7192 
    [ 3.750,  5.000) = 1505 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.277 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     16.721 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.340          ops/ms
ClientSimple.existUser                       thrpt         11.611          ops/ms
ClientSimple.getUser                         thrpt         12.279          ops/ms
ClientSimple.listUser                        thrpt          7.714          ops/ms
ClientSimple.createUser                       avgt          2.463           ms/op
ClientSimple.existUser                        avgt          1.779           ms/op
ClientSimple.getUser                          avgt          2.207           ms/op
ClientSimple.listUser                         avgt          3.524           ms/op
ClientSimple.createUser                     sample  15249   2.119 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.579           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.619           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.980           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.724           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.171           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.498           ms/op
ClientSimple.existUser                      sample  16234   1.969 ± 0.062   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.397           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.134           ms/op
ClientSimple.existUser:existUser·p0.999     sample         57.082           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         57.958           ms/op
ClientSimple.existUser:existUser·p1.00      sample         57.999           ms/op
ClientSimple.getUser                        sample  14585   2.202 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.757           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.066           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.950           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.054           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.152           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.152           ms/op
ClientSimple.listUser                       sample  10081   3.174 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.001           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.985           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.277           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.206           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.721           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.728           ms/op

Benchmark result is saved to 1716079351681.json
