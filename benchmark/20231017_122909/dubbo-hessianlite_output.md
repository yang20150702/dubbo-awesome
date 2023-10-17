# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.599 ops/ms
Iteration   1: 5.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.381 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.419 ops/ms
Iteration   1: 11.389 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.389 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.895 ops/ms
Iteration   1: 7.669 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.669 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.128 ops/ms
Iteration   1: 1.585 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.585 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 9.209 ±(99.9%) 0.150 ms/op
Iteration   1: 4.090 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.208 ±(99.9%) 0.089 ms/op
Iteration   1: 2.341 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.756 ±(99.9%) 0.157 ms/op
Iteration   1: 4.908 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.908 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 26.635 ±(99.9%) 1.018 ms/op
Iteration   1: 15.723 ±(99.9%) 0.141 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ±(99.9%) 0.267 ms/op
Iteration   1: 3.335 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   4.998 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   12.337 ms/op
                 createUser·p0.999:  26.704 ms/op
                 createUser·p0.9999: 28.869 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9578
  mean =      3.335 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2782 
    [ 2.500,  5.000) = 5839 
    [ 5.000,  7.500) = 549 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      4.998 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     26.704 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 3.663 ±(99.9%) 0.127 ms/op
Iteration   1: 1.700 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.413 ms/op
                 existUser·p0.90:   1.944 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  24.418 ms/op
                 existUser·p0.9999: 25.107 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18904
  mean =      1.700 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17830 
    [ 2.500,  5.000) = 672 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.413 ms/op
     p(90.0000) =      1.944 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     24.418 ms/op
     p(99.9900) =     25.107 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 9.038 ±(99.9%) 0.269 ms/op
Iteration   1: 4.097 ±(99.9%) 0.137 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   7.113 ms/op
                 getUser·p0.95:   9.923 ms/op
                 getUser·p0.99:   18.013 ms/op
                 getUser·p0.999:  48.299 ms/op
                 getUser·p0.9999: 54.591 ms/op
                 getUser·p1.00:   54.591 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8006
  mean =      4.097 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6831 
    [ 5.000, 10.000) = 790 
    [10.000, 15.000) = 238 
    [15.000, 20.000) = 71 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 15 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 14 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      7.113 ms/op
     p(95.0000) =      9.923 ms/op
     p(99.0000) =     18.013 ms/op
     p(99.9000) =     48.299 ms/op
     p(99.9900) =     54.591 ms/op
     p(99.9990) =     54.591 ms/op
     p(99.9999) =     54.591 ms/op
    p(100.0000) =     54.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.809 ±(99.9%) 0.810 ms/op
Iteration   1: 12.870 ±(99.9%) 0.271 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   12.263 ms/op
                 listUser·p0.90:   17.203 ms/op
                 listUser·p0.95:   20.570 ms/op
                 listUser·p0.99:   28.055 ms/op
                 listUser·p0.999:  39.135 ms/op
                 listUser·p0.9999: 41.026 ms/op
                 listUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2568
  mean =     12.870 ±(99.9%) 0.271 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10 
    [ 5.000, 10.000) = 555 
    [10.000, 15.000) = 1492 
    [15.000, 20.000) = 369 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.462 ms/op
     p(50.0000) =     12.263 ms/op
     p(90.0000) =     17.203 ms/op
     p(95.0000) =     20.570 ms/op
     p(99.0000) =     28.055 ms/op
     p(99.9000) =     39.135 ms/op
     p(99.9900) =     41.026 ms/op
     p(99.9990) =     41.026 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.381          ops/ms
Client.existUser                       thrpt         11.389          ops/ms
Client.getUser                         thrpt          7.669          ops/ms
Client.listUser                        thrpt          1.585          ops/ms
Client.createUser                       avgt          4.090           ms/op
Client.existUser                        avgt          2.341           ms/op
Client.getUser                          avgt          4.908           ms/op
Client.listUser                         avgt         15.723           ms/op
Client.createUser                     sample   9578   3.335 ± 0.073   ms/op
Client.createUser:createUser·p0.00    sample          1.264           ms/op
Client.createUser:createUser·p0.50    sample          2.716           ms/op
Client.createUser:createUser·p0.90    sample          4.998           ms/op
Client.createUser:createUser·p0.95    sample          6.775           ms/op
Client.createUser:createUser·p0.99    sample         12.337           ms/op
Client.createUser:createUser·p0.999   sample         26.704           ms/op
Client.createUser:createUser·p0.9999  sample         28.869           ms/op
Client.createUser:createUser·p1.00    sample         28.869           ms/op
Client.existUser                      sample  18904   1.700 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.527           ms/op
Client.existUser:existUser·p0.50      sample          1.413           ms/op
Client.existUser:existUser·p0.90      sample          1.944           ms/op
Client.existUser:existUser·p0.95      sample          2.695           ms/op
Client.existUser:existUser·p0.99      sample          8.339           ms/op
Client.existUser:existUser·p0.999     sample         24.418           ms/op
Client.existUser:existUser·p0.9999    sample         25.107           ms/op
Client.existUser:existUser·p1.00      sample         25.690           ms/op
Client.getUser                        sample   8006   4.097 ± 0.137   ms/op
Client.getUser:getUser·p0.00          sample          0.506           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          7.113           ms/op
Client.getUser:getUser·p0.95          sample          9.923           ms/op
Client.getUser:getUser·p0.99          sample         18.013           ms/op
Client.getUser:getUser·p0.999         sample         48.299           ms/op
Client.getUser:getUser·p0.9999        sample         54.591           ms/op
Client.getUser:getUser·p1.00          sample         54.591           ms/op
Client.listUser                       sample   2568  12.870 ± 0.271   ms/op
Client.listUser:listUser·p0.00        sample          2.462           ms/op
Client.listUser:listUser·p0.50        sample         12.263           ms/op
Client.listUser:listUser·p0.90        sample         17.203           ms/op
Client.listUser:listUser·p0.95        sample         20.570           ms/op
Client.listUser:listUser·p0.99        sample         28.055           ms/op
Client.listUser:listUser·p0.999       sample         39.135           ms/op
Client.listUser:listUser·p0.9999      sample         41.026           ms/op
Client.listUser:listUser·p1.00        sample         41.026           ms/op
