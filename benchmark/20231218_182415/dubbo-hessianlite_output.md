# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.152 ops/ms
Iteration   1: 5.632 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.632 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ops/ms
Iteration   1: 11.458 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.458 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ops/ms
Iteration   1: 9.001 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.001 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.991 ops/ms
Iteration   1: 3.361 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.361 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ±(99.9%) 0.060 ms/op
Iteration   1: 3.091 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.091 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.459 ±(99.9%) 0.039 ms/op
Iteration   1: 2.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.359 ±(99.9%) 0.110 ms/op
Iteration   1: 3.205 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.220 ±(99.9%) 0.286 ms/op
Iteration   1: 7.822 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.813 ±(99.9%) 0.300 ms/op
Iteration   1: 3.195 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   12.253 ms/op
                 createUser·p0.999:  27.556 ms/op
                 createUser·p0.9999: 28.213 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10011
  mean =      3.195 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1890 
    [ 2.500,  5.000) = 7854 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =     12.253 ms/op
     p(99.9000) =     27.556 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.061 ±(99.9%) 0.071 ms/op
Iteration   1: 1.887 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.671 ms/op
                 existUser·p0.95:   2.929 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.093 ms/op
                 existUser·p0.9999: 7.810 ms/op
                 existUser·p1.00:   8.389 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17068
  mean =      1.887 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 26 
    [1.000, 1.500) = 5025 
    [1.500, 2.000) = 6503 
    [2.000, 2.500) = 2761 
    [2.500, 3.000) = 2013 
    [3.000, 3.500) = 523 
    [3.500, 4.000) = 110 
    [4.000, 4.500) = 18 
    [4.500, 5.000) = 7 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 15 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      7.093 ms/op
     p(99.9900) =      7.810 ms/op
     p(99.9990) =      8.389 ms/op
     p(99.9999) =      8.389 ms/op
    p(100.0000) =      8.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ±(99.9%) 0.157 ms/op
Iteration   1: 3.048 ±(99.9%) 0.048 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.914 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  27.116 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10498
  mean =      3.048 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1940 
    [ 2.500,  5.000) = 8439 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.914 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     27.116 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.079 ±(99.9%) 0.404 ms/op
Iteration   1: 8.323 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   7.889 ms/op
                 listUser·p0.90:   11.436 ms/op
                 listUser·p0.95:   12.377 ms/op
                 listUser·p0.99:   17.378 ms/op
                 listUser·p0.999:  24.317 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3850
  mean =      8.323 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 187 
    [ 5.000,  7.500) = 1460 
    [ 7.500, 10.000) = 1358 
    [10.000, 12.500) = 666 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =     11.436 ms/op
     p(95.0000) =     12.377 ms/op
     p(99.0000) =     17.378 ms/op
     p(99.9000) =     24.317 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.632          ops/ms
Client.existUser                       thrpt         11.458          ops/ms
Client.getUser                         thrpt          9.001          ops/ms
Client.listUser                        thrpt          3.361          ops/ms
Client.createUser                       avgt          3.091           ms/op
Client.existUser                        avgt          2.049           ms/op
Client.getUser                          avgt          3.205           ms/op
Client.listUser                         avgt          7.822           ms/op
Client.createUser                     sample  10011   3.195 ± 0.061   ms/op
Client.createUser:createUser·p0.00    sample          1.085           ms/op
Client.createUser:createUser·p0.50    sample          2.961           ms/op
Client.createUser:createUser·p0.90    sample          3.756           ms/op
Client.createUser:createUser·p0.95    sample          4.137           ms/op
Client.createUser:createUser·p0.99    sample         12.253           ms/op
Client.createUser:createUser·p0.999   sample         27.556           ms/op
Client.createUser:createUser·p0.9999  sample         28.213           ms/op
Client.createUser:createUser·p1.00    sample         28.213           ms/op
Client.existUser                      sample  17068   1.887 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.713           ms/op
Client.existUser:existUser·p0.50      sample          1.667           ms/op
Client.existUser:existUser·p0.90      sample          2.671           ms/op
Client.existUser:existUser·p0.95      sample          2.929           ms/op
Client.existUser:existUser·p0.99      sample          3.637           ms/op
Client.existUser:existUser·p0.999     sample          7.093           ms/op
Client.existUser:existUser·p0.9999    sample          7.810           ms/op
Client.existUser:existUser·p1.00      sample          8.389           ms/op
Client.getUser                        sample  10498   3.048 ± 0.048   ms/op
Client.getUser:getUser·p0.00          sample          0.604           ms/op
Client.getUser:getUser·p0.50          sample          2.914           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          3.953           ms/op
Client.getUser:getUser·p0.99          sample          5.513           ms/op
Client.getUser:getUser·p0.999         sample         27.116           ms/op
Client.getUser:getUser·p0.9999        sample         27.427           ms/op
Client.getUser:getUser·p1.00          sample         27.427           ms/op
Client.listUser                       sample   3850   8.323 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          1.960           ms/op
Client.listUser:listUser·p0.50        sample          7.889           ms/op
Client.listUser:listUser·p0.90        sample         11.436           ms/op
Client.listUser:listUser·p0.95        sample         12.377           ms/op
Client.listUser:listUser·p0.99        sample         17.378           ms/op
Client.listUser:listUser·p0.999       sample         24.317           ms/op
Client.listUser:listUser·p0.9999      sample         25.821           ms/op
Client.listUser:listUser·p1.00        sample         25.821           ms/op
