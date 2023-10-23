# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 5.750 ops/ms
# Warmup Iteration   3: 8.972 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 9.655 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.623 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (9.584, 9.623, 9.655), stdev = 0.036
  CI (99.9%): [8.967, 10.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.018 ops/ms
# Warmup Iteration   2: 8.608 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 9.891 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.019 ±(99.9%) 5.516 ops/ms [Average]
  (min, avg, max) = (9.803, 10.019, 10.365), stdev = 0.302
  CI (99.9%): [4.504, 15.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.141 ops/ms
# Warmup Iteration   3: 9.593 ops/ms
Iteration   1: 9.935 ops/ms
Iteration   2: 9.972 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.883 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (9.743, 9.883, 9.972), stdev = 0.123
  CI (99.9%): [7.643, 12.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 7.901 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.333 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (8.318, 8.333, 8.352), stdev = 0.017
  CI (99.9%): [8.015, 8.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.891 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.004 ms/op
Iteration   1: 3.269 ±(99.9%) 0.004 ms/op
Iteration   2: 3.315 ±(99.9%) 0.003 ms/op
Iteration   3: 3.229 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.271 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (3.229, 3.271, 3.315), stdev = 0.043
  CI (99.9%): [2.486, 4.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.110 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.004 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.116 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.071, 3.116, 3.176), stdev = 0.054
  CI (99.9%): [2.124, 4.107] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.436 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.002 ms/op
Iteration   1: 3.259 ±(99.9%) 0.002 ms/op
Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.188, 3.238, 3.267), stdev = 0.044
  CI (99.9%): [2.437, 4.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.024 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.003 ms/op
Iteration   1: 3.876 ±(99.9%) 0.004 ms/op
Iteration   2: 3.848 ±(99.9%) 0.004 ms/op
Iteration   3: 3.854 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.859 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.848, 3.859, 3.876), stdev = 0.015
  CI (99.9%): [3.587, 4.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  15.994 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.902 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.452 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.067 ms/op
                 createUser·p0.999:  14.901 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298231
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14926 
    [ 2.500,  5.000) = 279470 
    [ 5.000,  7.500) = 2792 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 187 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     17.065 ms/op
     p(99.9900) =     22.222 ms/op
     p(99.9990) =     23.041 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.773 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  18.611 ms/op
                 existUser·p0.9999: 21.639 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.743 ms/op
                 existUser·p0.9999: 23.908 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299134
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13906 
    [ 2.500,  5.000) = 279075 
    [ 5.000,  7.500) = 5348 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     12.064 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.937 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.047 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
Iteration   1: 3.346 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  19.347 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.296 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291656
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8180 
    [ 2.500,  5.000) = 276431 
    [ 5.000,  7.500) = 6034 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     15.669 ms/op
     p(99.9900) =     23.287 ms/op
     p(99.9990) =     25.365 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.401 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  17.645 ms/op
                 listUser·p0.9999: 21.248 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 3.902 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.518 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 15.332 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 15.755 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246119
  mean =      3.899 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 238928 
    [ 5.000,  7.500) = 5698 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     20.362 ms/op
     p(99.9990) =     21.942 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.623 ± 0.656  ops/ms
ClientPb.existUser                       thrpt       3  10.019 ± 5.516  ops/ms
ClientPb.getUser                         thrpt       3   9.883 ± 2.241  ops/ms
ClientPb.listUser                        thrpt       3   8.333 ± 0.318  ops/ms
ClientPb.createUser                       avgt       3   3.271 ± 0.785   ms/op
ClientPb.existUser                        avgt       3   3.116 ± 0.992   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   3.859 ± 0.273   ms/op
ClientPb.createUser                     sample  298231   3.217 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.482           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.065           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.495           ms/op
ClientPb.existUser                      sample  299134   3.206 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.788           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.064           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.527           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  291656   3.288 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.326           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.669           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  246119   3.899 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.356           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.598           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.362           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
