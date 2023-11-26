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
# Warmup Iteration   1: 2.184 ops/ms
Iteration   1: 6.032 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.032 ops/ms


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
# Warmup Iteration   1: 5.826 ops/ms
Iteration   1: 13.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.372 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ops/ms
Iteration   1: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.209 ops/ms


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
# Warmup Iteration   1: 2.230 ops/ms
Iteration   1: 2.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.363 ops/ms


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.074 ms/op
Iteration   1: 2.947 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.947 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.063 ms/op
Iteration   1: 2.075 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.075 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.044 ms/op
Iteration   1: 2.750 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.750 ms/op


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
# Warmup Iteration   1: 11.860 ±(99.9%) 0.172 ms/op
Iteration   1: 8.243 ±(99.9%) 0.144 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.243 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.129 ms/op
Iteration   1: 3.084 ±(99.9%) 0.125 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   12.594 ms/op
                 createUser·p0.999:  72.421 ms/op
                 createUser·p0.9999: 79.648 ms/op
                 createUser·p1.00:   79.692 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10366
  mean =      3.084 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10047 
    [ 5.000, 10.000) = 161 
    [10.000, 15.000) = 75 
    [15.000, 20.000) = 40 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 5 
    [70.000, 75.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =     12.594 ms/op
     p(99.9000) =     72.421 ms/op
     p(99.9900) =     79.648 ms/op
     p(99.9990) =     79.692 ms/op
     p(99.9999) =     79.692 ms/op
    p(100.0000) =     79.692 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.058 ms/op
Iteration   1: 1.939 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.349 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   4.370 ms/op
                 existUser·p0.999:  12.905 ms/op
                 existUser·p0.9999: 15.245 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16492
  mean =      1.939 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 15461 
    [ 2.500,  3.750) = 462 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.370 ms/op
     p(99.9000) =     12.905 ms/op
     p(99.9900) =     15.245 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.106 ms/op
Iteration   1: 2.646 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   5.886 ms/op
                 getUser·p0.999:  13.566 ms/op
                 getUser·p0.9999: 13.807 ms/op
                 getUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12154
  mean =      2.646 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 6109 
    [ 2.500,  3.750) = 5430 
    [ 3.750,  5.000) = 358 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.886 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     13.807 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.646 ±(99.9%) 0.288 ms/op
Iteration   1: 7.526 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   7.127 ms/op
                 listUser·p0.90:   9.732 ms/op
                 listUser·p0.95:   10.928 ms/op
                 listUser·p0.99:   18.015 ms/op
                 listUser·p0.999:  24.684 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4235
  mean =      7.526 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 233 
    [ 5.000,  7.500) = 2355 
    [ 7.500, 10.000) = 1290 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.544 ms/op
     p(50.0000) =      7.127 ms/op
     p(90.0000) =      9.732 ms/op
     p(95.0000) =     10.928 ms/op
     p(99.0000) =     18.015 ms/op
     p(99.9000) =     24.684 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.032          ops/ms
Client.existUser                       thrpt         13.372          ops/ms
Client.getUser                         thrpt          8.209          ops/ms
Client.listUser                        thrpt          2.363          ops/ms
Client.createUser                       avgt          2.947           ms/op
Client.existUser                        avgt          2.075           ms/op
Client.getUser                          avgt          2.750           ms/op
Client.listUser                         avgt          8.243           ms/op
Client.createUser                     sample  10366   3.084 ± 0.125   ms/op
Client.createUser:createUser·p0.00    sample          0.670           ms/op
Client.createUser:createUser·p0.50    sample          2.617           ms/op
Client.createUser:createUser·p0.90    sample          3.478           ms/op
Client.createUser:createUser·p0.95    sample          4.121           ms/op
Client.createUser:createUser·p0.99    sample         12.594           ms/op
Client.createUser:createUser·p0.999   sample         72.421           ms/op
Client.createUser:createUser·p0.9999  sample         79.648           ms/op
Client.createUser:createUser·p1.00    sample         79.692           ms/op
Client.existUser                      sample  16492   1.939 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.349           ms/op
Client.existUser:existUser·p0.50      sample          1.858           ms/op
Client.existUser:existUser·p0.90      sample          2.347           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          4.370           ms/op
Client.existUser:existUser·p0.999     sample         12.905           ms/op
Client.existUser:existUser·p0.9999    sample         15.245           ms/op
Client.existUser:existUser·p1.00      sample         15.532           ms/op
Client.getUser                        sample  12154   2.646 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.868           ms/op
Client.getUser:getUser·p0.50          sample          2.490           ms/op
Client.getUser:getUser·p0.90          sample          3.346           ms/op
Client.getUser:getUser·p0.95          sample          3.699           ms/op
Client.getUser:getUser·p0.99          sample          5.886           ms/op
Client.getUser:getUser·p0.999         sample         13.566           ms/op
Client.getUser:getUser·p0.9999        sample         13.807           ms/op
Client.getUser:getUser·p1.00          sample         13.828           ms/op
Client.listUser                       sample   4235   7.526 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.544           ms/op
Client.listUser:listUser·p0.50        sample          7.127           ms/op
Client.listUser:listUser·p0.90        sample          9.732           ms/op
Client.listUser:listUser·p0.95        sample         10.928           ms/op
Client.listUser:listUser·p0.99        sample         18.015           ms/op
Client.listUser:listUser·p0.999       sample         24.684           ms/op
Client.listUser:listUser·p0.9999      sample         26.870           ms/op
Client.listUser:listUser·p1.00        sample         26.870           ms/op
