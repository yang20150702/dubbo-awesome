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
# Warmup Iteration   1: 1.788 ops/ms
Iteration   1: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.708 ops/ms


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
# Warmup Iteration   1: 6.399 ops/ms
Iteration   1: 13.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.299 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 13.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.706 ops/ms


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
# Warmup Iteration   1: 5.230 ops/ms
Iteration   1: 9.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.158 ops/ms


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.077 ms/op
Iteration   1: 2.202 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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
# Warmup Iteration   1: 3.040 ±(99.9%) 0.052 ms/op
Iteration   1: 1.693 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.693 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.068 ms/op
Iteration   1: 2.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.000 ms/op


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.136 ms/op
Iteration   1: 3.481 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.083 ms/op
Iteration   1: 2.266 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  19.559 ms/op
                 createUser·p0.9999: 20.315 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14096
  mean =      2.266 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10985 
    [ 2.500,  5.000) = 2870 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     19.559 ms/op
     p(99.9900) =     20.315 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 3.125 ±(99.9%) 0.084 ms/op
Iteration   1: 1.933 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.267 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.068 ms/op
                 existUser·p0.999:  39.677 ms/op
                 existUser·p0.9999: 43.853 ms/op
                 existUser·p1.00:   49.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16575
  mean =      1.933 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16475 
    [ 5.000, 10.000) = 32 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.267 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.068 ms/op
     p(99.9000) =     39.677 ms/op
     p(99.9900) =     43.853 ms/op
     p(99.9990) =     49.283 ms/op
     p(99.9999) =     49.283 ms/op
    p(100.0000) =     49.283 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.080 ms/op
Iteration   1: 1.873 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   1.714 ms/op
                 getUser·p0.90:   2.327 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.241 ms/op
                 getUser·p0.999:  24.017 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17065
  mean =      1.873 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15985 
    [ 2.500,  5.000) = 1013 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.241 ms/op
     p(99.9000) =     24.017 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.124 ms/op
Iteration   1: 3.342 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.359 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.015 ms/op
                 listUser·p0.999:  6.693 ms/op
                 listUser·p0.9999: 10.338 ms/op
                 listUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9581
  mean =      3.342 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 66 
    [ 2.000,  3.000) = 3408 
    [ 3.000,  4.000) = 4743 
    [ 4.000,  5.000) = 1267 
    [ 5.000,  6.000) = 72 
    [ 6.000,  7.000) = 22 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.015 ms/op
     p(99.9000) =      6.693 ms/op
     p(99.9900) =     10.338 ms/op
     p(99.9990) =     10.338 ms/op
     p(99.9999) =     10.338 ms/op
    p(100.0000) =     10.338 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.708          ops/ms
ClientSimple.existUser                       thrpt         13.299          ops/ms
ClientSimple.getUser                         thrpt         13.706          ops/ms
ClientSimple.listUser                        thrpt          9.158          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.693           ms/op
ClientSimple.getUser                          avgt          2.000           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  14096   2.266 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.468           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.217           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.559           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.315           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.382           ms/op
ClientSimple.existUser                      sample  16575   1.933 ± 0.043   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.267           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.068           ms/op
ClientSimple.existUser:existUser·p0.999     sample         39.677           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         43.853           ms/op
ClientSimple.existUser:existUser·p1.00      sample         49.283           ms/op
ClientSimple.getUser                        sample  17065   1.873 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.544           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.241           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.017           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.084           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.084           ms/op
ClientSimple.listUser                       sample   9581   3.342 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.077           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.359           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.015           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.693           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.338           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.338           ms/op

Benchmark result is saved to 1714783071445.json
