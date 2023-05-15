# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.785 ops/ms
# Warmup Iteration   2: 4.140 ops/ms
# Warmup Iteration   3: 7.767 ops/ms
Iteration   1: 7.709 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.148 ±(99.9%) 6.978 ops/ms [Average]
  (min, avg, max) = (7.709, 8.148, 8.409), stdev = 0.383
  CI (99.9%): [1.170, 15.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.355 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 7.916 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.761 ops/ms
Iteration   3: 8.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.556 ±(99.9%) 5.312 ops/ms [Average]
  (min, avg, max) = (8.223, 8.556, 8.761), stdev = 0.291
  CI (99.9%): [3.244, 13.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 7.817 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.293 ±(99.9%) 5.851 ops/ms [Average]
  (min, avg, max) = (7.975, 8.293, 8.617), stdev = 0.321
  CI (99.9%): [2.443, 14.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.344 ops/ms
# Warmup Iteration   2: 5.524 ops/ms
# Warmup Iteration   3: 6.776 ops/ms
Iteration   1: 6.722 ops/ms
Iteration   2: 6.885 ops/ms
Iteration   3: 6.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.861 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (6.722, 6.861, 6.976), stdev = 0.129
  CI (99.9%): [4.516, 9.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.426 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.005 ms/op
Iteration   1: 3.808 ±(99.9%) 0.006 ms/op
Iteration   2: 3.776 ±(99.9%) 0.007 ms/op
Iteration   3: 3.781 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.788 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.776, 3.788, 3.808), stdev = 0.017
  CI (99.9%): [3.473, 4.104] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.998 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.004 ms/op
Iteration   1: 3.602 ±(99.9%) 0.008 ms/op
Iteration   2: 3.574 ±(99.9%) 0.013 ms/op
Iteration   3: 3.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.690 ±(99.9%) 3.225 ms/op [Average]
  (min, avg, max) = (3.574, 3.690, 3.894), stdev = 0.177
  CI (99.9%): [0.465, 6.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.602 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.921 ±(99.9%) 0.004 ms/op
Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
Iteration   3: 3.660 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.780 ±(99.9%) 2.403 ms/op [Average]
  (min, avg, max) = (3.660, 3.780, 3.921), stdev = 0.132
  CI (99.9%): [1.377, 6.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.441 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.948 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.188 ±(99.9%) 0.005 ms/op
Iteration   1: 4.601 ±(99.9%) 0.011 ms/op
Iteration   2: 4.421 ±(99.9%) 0.010 ms/op
Iteration   3: 4.288 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.437 ±(99.9%) 2.863 ms/op [Average]
  (min, avg, max) = (4.288, 4.437, 4.601), stdev = 0.157
  CI (99.9%): [1.574, 7.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.165 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.137 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.018 ms/op
Iteration   1: 3.878 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   5.029 ms/op
                 createUser·p0.99:   7.125 ms/op
                 createUser·p0.999:  23.412 ms/op
                 createUser·p0.9999: 26.557 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.816 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   7.446 ms/op
                 createUser·p0.999:  24.419 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 3.874 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  27.256 ms/op
                 createUser·p0.9999: 31.916 ms/op
                 createUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249054
  mean =      3.855 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 674 
    [ 2.500,  5.000) = 237084 
    [ 5.000,  7.500) = 9252 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     24.084 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     32.477 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 10.586 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  22.968 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.811 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.752 ms/op
                 existUser·p0.999:  16.388 ms/op
                 existUser·p0.9999: 27.283 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 4.114 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  28.611 ms/op
                 existUser·p0.9999: 31.766 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244796
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 507 
    [ 2.500,  5.000) = 228503 
    [ 5.000,  7.500) = 13993 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     22.485 ms/op
     p(99.9900) =     30.296 ms/op
     p(99.9990) =     32.083 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.071 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.017 ms/op
Iteration   1: 4.171 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  26.024 ms/op
                 getUser·p0.9999: 32.484 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 30.424 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 4.153 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.897 ms/op
                 getUser·p0.999:  29.229 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235126
  mean =      4.082 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 217761 
    [ 5.000,  7.500) = 14085 
    [ 7.500, 10.000) = 2393 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     25.526 ms/op
     p(99.9900) =     32.603 ms/op
     p(99.9990) =     36.392 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.133 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.536 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.710 ±(99.9%) 0.017 ms/op
Iteration   1: 4.554 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  26.562 ms/op
                 listUser·p0.9999: 29.917 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   2: 4.928 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 23.332 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.751 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.895 ms/op
                 listUser·p0.9999: 22.562 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202426
  mean =      4.740 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 169105 
    [ 5.000,  7.500) = 27568 
    [ 7.500, 10.000) = 4569 
    [10.000, 12.500) = 548 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.991 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     30.047 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.148 ± 6.978  ops/ms
ClientPb.existUser                       thrpt       3   8.556 ± 5.312  ops/ms
ClientPb.getUser                         thrpt       3   8.293 ± 5.851  ops/ms
ClientPb.listUser                        thrpt       3   6.861 ± 2.345  ops/ms
ClientPb.createUser                       avgt       3   3.788 ± 0.315   ms/op
ClientPb.existUser                        avgt       3   3.690 ± 3.225   ms/op
ClientPb.getUser                          avgt       3   3.780 ± 2.403   ms/op
ClientPb.listUser                         avgt       3   4.437 ± 2.863   ms/op
ClientPb.createUser                     sample  249054   3.855 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.084           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.326           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  244796   3.921 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.475           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.485           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.296           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  235126   4.082 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.603           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.504           ms/op
ClientPb.listUser                       sample  202426   4.740 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.991           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.300           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.218           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.327           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.081           ms/op
